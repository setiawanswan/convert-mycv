<template>
<div>
    <b-container class="title-three">
        <b-row>
            <b-col>
                <p class="title">What I Do</p>
            </b-col>
        </b-row>
    </b-container>
    <b-container class="section-three">
        <b-row>
            <b-col xs="12" md="12">
                <b-card class="shadow p-3 mb-5 bg-body rounded border">
                    <b-icon icon="code-slash" font-scale="2" class="do-icon"></b-icon>
                    <p class="title-card">Web Development</p>
                    <b-card-text class="text">
                        Lorem ipsum dolor sit amet, consectetuer adipiscing elit, 
                        sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.
                    </b-card-text>
                </b-card>
            </b-col>
            <b-col xs="12" md="12">
                <b-card class="shadow p-3 mb-5 bg-body rounded border">
                    <b-icon icon="book" font-scale="2" class="do-icon"></b-icon>
                    <p class="title-card">Read Book</p>
                    <b-card-text class="text">
                        Lorem ipsum dolor sit amet, consectetuer adipiscing elit, 
                        sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.
                    </b-card-text>
                </b-card>
            </b-col>
            <b-col xs="12" md="12">
                <b-card class="shadow p-3 mb-5 bg-body rounded border">
                    <b-icon icon="chevron-down" font-scale="2" class="do-icon"></b-icon>
                    <p class="title-card">Design</p>
                    <b-card-text class="text">
                        Lorem ipsum dolor sit amet, consectetuer adipiscing elit, 
                        sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.
                    </b-card-text>
                </b-card>
            </b-col>
        </b-row>
    </b-container>
</div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.title-three{
    text-align: center;
}

.title{
    font-family: sans-serif;
    font-size: 30px;
    /* font-weight: 600; */
}

.do-icon{
    color: #00BFA6;
}

.title-card{
    margin-top: 4%;
    font-weight: 600;
    font-size: 20px;
}

.section-three{
    padding: 5%;
    
}

.border{
    border: none !important;
}

@media only screen and (max-width: 650px) { 
    .title {
        font-size: 24px;
    }
}

@media only screen and (max-width: 650px) { 
    .section-three {
        text-align: center;
    }
}
@media only screen and (max-width: 650px) { 
    .title-card {
        font-size: 17px;
    }
}
@media only screen and (max-width: 650px) { 
    .text {
        font-size: 14px;
    }
}
</style>