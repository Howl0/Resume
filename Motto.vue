<template>
    <div id="Favorite">
        <div id="right-info">
            <div class="container">
                <div class="fave" role="alert">
                    <ul>
                        <li>{{ food }}</li>
                        <li>{{ band }}</li>
                        <li>{{ fruit }}</li>
                        <li>{{ pet }}</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Favorite',
    data () {
        return {
            food: 'Food : Sisig',
            band: 'Band : Imagine Dragons',
            fruit: 'Fruit : Kiwi',
            pet: 'Pet : Dog'
        }
    }
}
</script>