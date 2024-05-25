<template>
    <div class="Header">
        <div class="NavBar">
            <div class="leftBar">oatkid</div>
			<div class="rightBar">
                <NuxtLink class="goPage" to="#">Home</NuxtLink>
                <NuxtLink class="goPage" to="#">Skill</NuxtLink>
                <NuxtLink class="goPage" to="#">Achievement</NuxtLink>
                <NuxtLink class="goPage" to="#">About</NuxtLink>
            </div>
        </div>
        <div class="HomeImg">
            <img src="/assets/img/homepage.jpg"/>
            <div class="profile">
                <div class="speech">
                    <h2>
                        <span>Hi</span>
                        <br>
                        I'm Siwakorn Pasawang (Oat).
                        <br>
                        I achieve my projects !!
                        
                    </h2>
                </div>
                <div class="profileImg">
                    <img src="~/assets/img/profile.jpg" alt="" srcset="">
                </div>
            </div>
        </div>
    </div>

    <div class="Section">
        <div class="topic"><h2>Personal Information</h2></div>
        <div class="content">
            <ul>
                <li>Fullname : Mr. Siwakorn Pasawang</li>
                <li>Nickname : Oat</li>
                <li>High School : Debsirin Nonthaburi School</li>
                <li>University : Kasetsart University</li>
                <li>Home Contry : Thailand</li>
            </ul>
        </div>

        <div class="topic"><h2>Contact</h2></div>
        <div class="content">
            <ul>
                <li>E-mail : pasawang.sivakorn@gmail.com</li>
                <li>Facebook : Siwakorn Pasawang</li>
                <li>Github : OatKID</li>
                <li>Discord : OatKID</li>
            </ul>
        </div>

        <div class="topic"><h2>Hard Skill</h2></div>
        <div class="content">
            <ul>
                <li>
                    Programming Language
                    <ul>
                        <li>Python</li>
                        <li>C/C++</li>
                        <li>Java</li>
                    </ul>
                </li>

                <li>
                    Frameworks
                    <ul>
                        <li>Spring Boot</li>
                        <li>Nuxt JS</li>
                        <li>Tailwind CSS</li>
                        <li>Next JS</li>
                        <li>Java FX</li>
                    </ul>
                </li>

                <li>
                    Other
                    <ul>
                        <li>Unix</li>
                        <li>Arduino</li>
                        <li>Machine Learning</li>
                        <li>MySQL</li>
                        <li>Docker</li>
                    </ul>
                </li>
            </ul>
        </div>
    </div>

</template>

<script>
    
</script>