<template>
    <header>
        <div class="container">
            <img class="headerImg" src="./assets/header.png" />
            <div class="centered">
                <h1>{{ header }}</h1>
                <p class="headerText"> {{ text }} </p>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    data () {
        return {
            header: 'Main heading here',
            text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ultricies mi eget mauris',
            buttonOne: 'Button One',
            buttonTwo: 'Button Two',
            btnText: 'Lorem Ipsum Dolor Sit',
        }
    }
}
</script>