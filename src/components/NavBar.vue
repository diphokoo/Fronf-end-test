<template>
    <section class="navigation"> 
        <div class="nav-container">
            <div class="company-logo">
                <h2>Exigent <span class="logo">Logo</span></h2>
            </div>
            <nav>
                <div class="nav-mobile">
                    <a id="nav-toggle" href="#!"><span></span></a>
                </div>
                <ul class="nav-list">
                    <li><a href="#!">Item 1</a></li>
                    <li><a href="#!">Item 2</a></li>
                    <li><a href="#!">Item 3</a></li>
                    <li><a href="#!">Item 4</a></li>
                    <li><a href="#!">Item 5</a></li>
                    <li><a type="button" href="#!" class="btn">Button</a></li>
                </ul>
            </nav>
        </div>
        
    </section>
</template>

<script>
 export default {
    name: 'NavBar',
    props:{
        nav: Array,
    }   
 }
</script>
