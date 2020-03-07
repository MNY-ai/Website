<template>
    <div class="ht-tab-wrap">
        <b-tabs class="ht-tab-menu wow move-up">
        <b-tab title="Mission">
            <!-- tab content two component -->
            <TabContentTwo />
        </b-tab>
            <b-tab title="Careers" active>
                <TabContentOne />
            </b-tab>
            <b-tab title="Cultures" active>
                <TabContentFive />
            </b-tab>
            <b-tab title="Benefits">
                <TabContentFour />
            </b-tab>
        </b-tabs>
    </div>
</template>

<script>
    import TabContentOne from '../components/TabContentOne'
    import TabContentTwo from '../components/TabContentTwo'
    import TabContentThree from '../components/TabContentThree'
    import TabContentFour from '../components/TabContentFour'
    import TabContentFive from '../components/TabContentFive'

    export default {
        name: 'TabTwo',
        components: {
            TabContentOne,
            TabContentTwo,
            TabContentThree,
            TabContentFour,
            TabContentFive
        }
    };
</script>
