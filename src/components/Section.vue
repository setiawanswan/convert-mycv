<template>
    <b-container class="section-one">
        <b-row>
            <b-col xs="12">
                <div>
                    <p class="fullName">Setiawan</p>
                </div>
                <div>
                    <p class="myRole">Frontend Developer</p>
                </div>
                <div>
                    <p class="text"> <b-icon icon="phone-fill" class="identity"></b-icon> +62 85365653941</p>
                    <p class="text"><b-icon icon="envelope-fill" class="identity"></b-icon> setiawan.tumilin@gmail.com</p>
                    <p class="text"><b-icon icon="linkedin" class="identity"></b-icon> Setiawan Tumilin</p>
                    <p class="text"><b-icon icon="geo-fill" class="identity"></b-icon> Jln H.Umar No 33 (Sukabirus)Kab.Bandung, West Java PO Box, 40288 Indonesia</p>
                </div>
            </b-col>
            <b-col xs="12">
                <div class="circle">
                    <img class="ava" src="../assets/wankuy.png" alt="" width="50%">
                </div>
            </b-col>
        </b-row>
    </b-container>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.section-one{
    padding: 8%;
}

.fullName {
    font-family: sans-serif;
    font-size: 50px;
}

.myRole {
    font-family: sans-serif;
    font-size: 30px;
}

.text{
    color: #717171;
    font-size: 16px;
}

.identity{
    color: #00BFA6;
}

.right-section{
    text-align: center;
}

.ava{
    /* border: 1px solid black; */
    border-radius: 60%;
    background-color: #00BFA6;
}

@media only screen and (max-width: 650px) { 
    .section-one {
        text-align: center;
    }
}

@media only screen and (max-width: 650px) { 
    .section-one {
        text-align: center;
    }
}

@media only screen and (max-width: 650px) { 
    .fullName {
        font-size: 30px;
    }
}

@media only screen and (max-width: 650px) { 
    .myRole {
        font-size: 20px;
    }
}

@media only screen and (max-width: 650px) { 
    .text {
        font-size: 14px;
    }
}

@media only screen and (max-width: 650px) { 
    .ava {
        display: none;
    }
}
</style>