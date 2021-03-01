<template>
<div class="background">
    <b-container class="section-four">
        <b-row>
            <b-col xs="12" md="12">
                <p class="title-section">Education</p>
                <b-card class="shadow p-3 mb-5 bg-body rounded border">
                    <p class="title">Telkom University</p>
                    <p class="subtitle"> <i>Bachelor Degree Of Industrial Engineering</i></p>
                    <p class="date">Aug, 2016 - Feb, 2021</p>
                    <b-card-text>
                        <ul>
                            <li class="list" v-for="edus in edu" :key="edus.id">
                                {{ edus.education }}
                            </li>
                        </ul>
                    </b-card-text>
                </b-card>
                <b-card class="shadow p-3 mb-5 bg-body rounded border">
                    <p class="title">Refactory.id</p>
                    <p class="subtitle"> <i>Backend Programming Certification</i></p>
                    <p class="date">Aug, 2018 - Oct, 2018</p>
                    <ul>
                        <li class="list" v-for="certifs in certif" :key="certifs.id">
                            {{ certifs.certification }}
                        </li>
                    </ul>
                </b-card>
            </b-col>
            <b-col xs="12" md="12">
                <p class="title-section">Work Experience</p>
                <b-card class="shadow p-3 mb-5 bg-body rounded border">
                    <p class="title">Atourin</p>
                    <p class="subtitle"> <i>Frontend Developer Intern</i> </p>
                    <p class="date">June, 2019 - Sept, 2019</p>
                    <b-card-text>
                        <ul>
                            <li class="list" v-for="lists in list" :key="lists.id">
                                {{ lists.atourin }}
                            </li>
                        </ul>
                    </b-card-text>
                </b-card>
                <b-card class="shadow p-3 mb-5 bg-body rounded border">
                    <p class="title">Fabelio</p>
                    <p class="subtitle"> <i>Frontend Developer Intern</i> </p>
                    <p class="date">Oct, 2018 - Dec, 2018</p>
                    <ul>
                        <li class="list" v-for="datas in data" :key="datas.id">
                            {{ datas.fabelio}}
                        </li>
                    </ul>
                </b-card>
            </b-col>
        </b-row>
    </b-container>
</div>
</template>

<script>
export default {
    data(){
        return{
            certif:[
                {certification: 'Javascript and NodeJs Learning'},
            ],

            edu: [
                {education: 'GPA : 3.33 of 4.00'},
                {education: 'Thesis : Design Of Customer Segmentation Using With Clustering K-Means Method and RFM Model In Seoul Secret Dermatology Clinic'}
            ],

            list:[
                { atourin: 'Create Company Website Volume 2 by using VueJs, HTML, SCSS coding Technology'},
                { atourin: 'Weekly Meeting Coordination with Lead and team member'}
            ],

            data: [
                { fabelio: 'Create Company Web page by using UI/UX'},
                { fabelio: 'Fixing bug in Company Website'},
                { fabelio: 'Weekly Meeting Coordination with Lead and team member'},
                { fabelio: 'Optimize website for maximum speed and scalability'}
            ]
        }
    }
}
</script>

<style scoped>
.section-four{
    padding: 6%;
}

.title-section{
    font-family: sans-serif;
    font-size: 30px;
    /* font-weight: 600; */
}

.title{
    font-family: sans-serif;
    font-size: 24px;
}

.subtitle{
    font-family: sans-serif;
    font-size: 20px;
    color: #00BFA6
}

.border{
    border: none !important ;
}

@media only screen and (max-width: 650px) { 
    .title-section {
        font-size: 24px;
        text-align: center;
    }
}

@media only screen and (max-width: 650px) { 
    .title {
        font-size: 20px;
    }
}

@media only screen and (max-width: 650px) { 
    .subtitle {
        font-size: 16px;
    }
}

@media only screen and (max-width: 650px) { 
    .date {
        font-size: 14px;
    }
}

@media only screen and (max-width: 650px) { 
    .list {
        font-size: 14px;
    }
}

</style>