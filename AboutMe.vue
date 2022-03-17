<template>
    <div id="about-me">
        <div id="right">
            <div class="container">
                <div class="right-info" role="alert">
                    <p> {{msg}} <br> <br> {{ msg1 }} </p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'about-me',
    data () {
        return {
            msg: 'I like doing stuff that challange me for me to grow even more.',
            msg1: 'One can choose to go back toward safety or forward toward growth'
        }
    }
}
</script>