<template>
    <div role="header">
        <header>
            <div class="wrapper">
                <nav>
                    <RouterLink to="/">Home</RouterLink>
                    <RouterLink to="/about">About</RouterLink>
                </nav>
            </div>
        </header>
    </div>
</template>

<script>
import { RouterLink } from 'vue-router'
export default {
    components: {
        RouterLink,
    }
}
</script>