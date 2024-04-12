<template>
    <div>
        <div id="header" class="clearfix">
            
            <router-link to="/">
                <img id="logo" src="@/assets/img/로고.png" alt="conan" width="150px" />
            </router-link>
            
        </div>
        <!-- //header -->
        <nav id="nav">
            
        </nav>
    </div> 
</template>
<script>
import '@/assets/css/AppHeader.css'

export default {
    name: "AppHeader",
    components: {},
    data() {
        return {};
    },
    methods: {
    },
    created() { }
};
</script>