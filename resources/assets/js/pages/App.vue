<template>
    <div>
        <app-header></app-header>
        <router-view></router-view>
        <!-- <app-footer></app-footer> -->
    </div>
</template>

<script>
import Header from './Header';
import Footer from './Footer';

export default {
    components: { 'app-header': Header, 'app-footer': Footer }
}
</script>
