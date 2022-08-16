<script>

</script>

<template>
    <section class="skills">
            <h2><span>My Skill</span></h2>
            <div class="skill">
                <div class="skill-image"><img src="/src/assets/software-engineer.png" alt="software engineer" ></div>
                    <div class="progress">    
                       <article class="progres">
                        <div class="progres-title"><img src="/src/assets/django.svg" alt="django" width="25"></div>
                        <el-progress :text-inside="true"  :stroke-width="26" :percentage="80" />
                        </article>
                        <article class="progres">
                        <div class="progres-title"><img src="/src/assets/python.svg" alt="python" width="25"></div>
                        <el-progress :text-inside="true" status="success" :stroke-width="26" :percentage="30" />
                        </article>
                        <article class="progres">
                        <div class="progres-title"><img src="/src/assets/html.svg" alt="html" width="25"></div>
                        <el-progress :text-inside="true" status="warning" :stroke-width="26" :percentage="90" />
                        </article>
                        <article class="progres">
                        <div class="progres-title"><img src="/src/assets/css3.svg" alt="css" width="25"></div>
                        <el-progress :text-inside="true" status="exception" :stroke-width="26" :percentage="80" />
                        </article>
                        <article class="progres">
                        <div class="progres-title"><img src="/src/assets/file.svg" alt="sql" width="30"></div>
                        <el-progress :text-inside="true" :stroke-width="26" :percentage="40" />
                        </article>
                        <article class="progres">
                        <div class="progres-title"><img src="/src/assets/bootstrap.svg" alt="sql" width="30"></div>
                        <el-progress :text-inside="true" :stroke-width="26" status="warning" :percentage="60" />
                        </article>
                        <article class="progres">
                        <div class="progres-title"><img src="/src/assets/vuejs.svg" alt="vuejs" width="30"></div>
                        <el-progress :text-inside="true" status="success" :stroke-width="26" :percentage="15" />
                        </article>
                    </div>
                </div>
        </section>
</template>