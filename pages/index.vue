<template>
    <div class="Header">
        <div class="NavBar">
            <div class="leftBar">oatkid</div>
			<div class="rightBar">
                <NuxtLink class="goPage" to="#">Home</NuxtLink>
                <NuxtLink class="goPage" to="#">Skill</NuxtLink>
                <NuxtLink class="goPage" to="#">Project</NuxtLink>
                <NuxtLink class="goPage" to="#">About</NuxtLink>
            </div>
            <div class="menuIcon" @click="showMenu"><Icon name="material-symbols:menu" /></div>
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

    <div class="menuPage" id="menuList">
            <div class="closeMark" @click="closeMenu"><Icon name="entypo:cross" size="32px"/></div>
            <div class="listGoPage">
                <NuxtLink class="goPage" to="#">Home</NuxtLink>
                <NuxtLink class="goPage" to="#">Skill</NuxtLink>
                <NuxtLink class="goPage" to="#">Project</NuxtLink>
                <NuxtLink class="goPage" to="#">About</NuxtLink>
            </div>
    </div>

    <div class="Section">
        <div class="topic"><h2>Personal Information</h2></div>
        <div class="content">
            <ul>
                <li><span>Fullname</span> : Mr. Siwakorn Pasawang</li>
                <li><span>Nickname</span> : Oat</li>
                <li><span>High School</span> : Debsirin Nonthaburi School</li>
                <li><span>University</span> : Kasetsart University</li>
                <li><span>Home Contry</span> : Thailand</li>
            </ul>
        </div>

        <div class="topic"><h2>Hard Skills</h2></div>
        <div class="content">
            <ul>
                <li>
                    <span>Programming Languages</span>
                    <ul>
                        <li>Python</li>
                        <li>C/C++</li>
                        <li>Java</li>
                        <li>MySQL</li>
                        <li>Assembly</li>
                    </ul>
                </li>

                <li>
                    <span>Frameworks</span>
                    <ul>
                        <li>Spring Boot</li>
                        <li>Nuxt JS</li>
                        <li>Tailwind CSS</li>
                        <li>Next JS</li>
                        <li>Java FX</li>
                    </ul>
                </li>

                <li>
                    <span>Fundametals of Computer Science</span>
                    <ul>
                        <li>Software Engineer</li>
                        <li>Artificial Intelligence</li>
                        <li>Machine Learning</li>
                        <li>Unix</li>
                    </ul>
                </li>
            </ul>
        </div>

        <div class="topic"><h2>Contacts</h2></div>
        <div class="content">
            <ul>
                <li><span>E-mail</span> : pasawang.sivakorn@gmail.com</li>
                <li><span>Facebook</span> : Siwakorn Pasawang</li>
                <li><span>Github</span> : OatKID</li>
                <li><span>Discord</span> : OatKID</li>
            </ul>
        </div>


    </div>

</template>

<script setup lang="ts">
    function showMenu(){
        const menuList = document.getElementById("menuList");
        menuList.style.width = "200px";
    };

    function closeMenu(){
        const menuList = document.getElementById("menuList");
        menuList.style.width = "0";
    };
</script>