<template>
    <b-container class="section-two" fluid="md">
        <b-row>
            <b-col xs="12" md="12">
                <div class="left-section">
                    <img src="../assets/office.png" alt="" width="80%">
                </div>
            </b-col>
            <b-col xs="12" md="12">
                <div class="right-section">
                    <div>
                        <p class="aboutMe">About Me</p>
                    </div>
                    <div>
                        <p class="textMe">I am a programmer Engineer enthusiast with self-taught skill, quick learner, easy adaptable, 
                            problem solving, good communication and can work as a team
                        </p>
                    </div>
                    <div class="skills-section">
                        <p v-for="todo in todos" :key="todo.id" class="skills">
                            {{ todo.skils}}
                        </p>
                    </div>
                    <div>
                        <button class="downloadCV">Download CV <b-icon icon="cloud-download-fill"></b-icon></button>
                    </div>
                </div>
            </b-col>
        </b-row>
    </b-container>
</template>

<script>
export default {
    data(){
        return{
            todos: [
                {skils : 'HTML'},
                {skils : 'CSS'},
                {skils : 'VueJs'},
                {skils : 'ReactJs'},
                {skils : 'NodeJs'},
                // {skils : 'Bootstrap'}
            ]
        }
    }
}
</script>

<style scoped>
.left-section{
    text-align: center;
}

.section-two{
    padding: 6%;
}

.right-section {
    text-align: left;
}

.aboutMe {
    font-family: sans-serif;
    font-size: 30px;
}

.textMe {
    font-family: sans-serif;
    font-size: 18px;
    color: #717171;
    /* font-weight: 600; */
}

.skills-section{
    display: flex;
    justify-content: space-between;
}

.skills{
    border: 1px solid #00BFA6;
    border-radius: 8px;
    padding: 6px 12px;
    font-size: 16px;
    color: #717171;
}

.downloadCV {
    font-family: sans-serif;
    font-size: 16px;
    padding: 8px 20px;
    border: none;
    border-radius: 30px;
    background-color: #00BFA6;
    color: white;
}

@media only screen and (max-width: 650px) { 
    .section-two {
        padding: 12%;
    }
}


@media only screen and (max-width: 650px) { 
    .aboutMe {
        font-size: 24px;
    }
}

@media only screen and (max-width: 650px) { 
    .right-section {
        text-align:center;
    }
}
@media only screen and (max-width: 650px) { 
    .textMe {
        font-size: 14px;
    }
}
@media only screen and (max-width: 650px) { 
    .skills{
        font-size: 14px;
    }
}
@media only screen and (max-width: 650px) { 
    .downloadCV {
        font-size: 14px;
    }
}
</style>