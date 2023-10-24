<script setup>

</script>

<template>
    <main class="container">
        <img
        class="mainImg"
         src="assets\images\image-web-3-desktop.jpg" alt="web 3 Image">
        <section class="mainBody">
            <h1 class="mainTitle">The Bright Future of Web 3.0?</h1>
            <div class="mainCont">
                <p>We dive into the next evolution of the web that claims to put the power of the platforms back into the hands of the people. But is it really fulfilling its promise?</p>
            <button id="readMore-btn">READ MORE</button>
            </div>
            
        </section>
    </main>
 
</template>

<style scoped>

.container {
    display: flex;
    flex-direction: column;
    max-width: 75%;
    padding-right: 25px;
}
.mainImg {
    max-width: 100%;
}

.mainBody {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    max-width: 100%;
    padding: 25px;
    margin-bottom: 25px;
    margin-top: 15px;
}
.mainTitle {
    color: var(--veryDarkBlue);
    font-size: 50px;
    font-weight: 800;
}
.mainCont {
    display: flex;
    flex-direction: column;
    padding-top: 0;
    padding-right: 0;
    padding-bottom: 5vh;
    padding-left: 20vw;
    line-height: 2em;
}

.mainCont p {
    color: var(--darkGrayishBlue);
    font-size: 17px;
    font-weight: 400;
    text-align: left;
}

#readMore-btn {
    background-color: var(--softRed);
    color: var(--offWhite);
    padding: 15px;
    margin-top: 27%;
    font-family: 'Inter', sans-serif;
    font-size: 1.2em;
    border: none;
}

#readMore-btn:hover {
    background-color: var(--softOrange);
    cursor: pointer;
}



@media screen and (min-width: 0px) and (max-width: 375px) {
    .container {
        max-width: 90vw;
        margin-right: 1%;
        padding: 0;
    }
    .mainBody {
        display: flex;
        flex-direction: column;
        width: 100vw;
        padding-left: 0;
    }
    
    .mainImg {
        height: 400px;
    }

    .mainTitle {
        width: 100%;
    }

    .mainCont {
        padding: 0;
    }

    #readMore-btn {
        width: 66%;
    }
}
</style>
