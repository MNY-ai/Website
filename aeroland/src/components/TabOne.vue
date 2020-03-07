<template>
    <div class="ht-tab-wrap">
        <b-tabs class="ht-tab-menu wow move-up">
        <b-tab title="Mission" active>
            <!-- tab content two component -->
            <TabContentTwo />
        </b-tab>
            <b-tab title="Careers>
                <TabContentOne />
            </b-tab>
            <b-tab title="Cultures">
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
        name: 'TabOne',
        components: {
            TabContentOne,
            TabContentTwo,
            TabContentThree,
            TabContentFour,
            TabContentFive
        }
    };
</script>
