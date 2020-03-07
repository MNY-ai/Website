<template>
    <div class="row">
        <div v-for="item in items" :key="item.id" class="col-lg-4 col-md-6 wow move-up">
            <div class="service-grid">
                <div class="ht-service-box--two text-center style-03">
                    <router-link to="">
                        <div class="image mb-20">
                            <img :src="item.icon" class="img-fluid" alt="aeroland-startup-box-icon-01">
                        </div>
                        <div class="content">
                            <h6 class="heading">{{ item.heading }}</h6>
                            <div class="service_text">{{ item.text }}</div>
                        </div>
                    </router-link>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'StartUpFeatureTwo',
        data (){
            return {
                items: [
                    {
                       icon: require('../assets/img/icons/aeroland-startup-box-icon-01.png'),
                       heading: 'Work From Home',
                       text: 'Work from any location you want to as long as you have access to the Internet you can work.'
                    },
                    {
                        icon: require('../assets/img/icons/aeroland-startup-box-icon-02.png'),
                        heading: 'Available Benefits',
                        text: 'If you meet the minimum time requirements, MNY can provide you with health care and benefits.'
                    },
                    {
                        icon: require('../assets/img/icons/aeroland-startup-box-icon-03.png'),
                        heading: 'On Your Schedule',
                        text: 'Pick your schedule, and work as little or as much as you like to  you can change it weekly.'
                    }
                ]
            }
        }
    }
</script>
