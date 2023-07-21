<template>
    <div>
        
        <AppHeader />
        
      
        <AppBanner />
        <Appcontent />
        <AppFooter />
    </div>
</template>

<script>
import AppHeader from '~/components/Eventmanagement/AppHeader.vue';
import AppFooter from '~/components/Eventmanagement/AppFooter.vue';
import AppBanner from '~/components/Eventmanagement/AppBanner.vue';
import Appcontent from '~/components/Eventmanagement/Appcontent.vue';

export default {
    name: 'default',
    components:{
        AppHeader,
        AppBanner,
        Appcontent,
        AppFooter
    }
}

</script>
