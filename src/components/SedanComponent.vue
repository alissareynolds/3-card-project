<template>
    <div id="sedan-frame">
        <div class="flex">
            <svg class="icon" width="64" height="40" xmlns="http://www.w3.org/2000/svg"><g fill="none" fill-rule="evenodd"><circle fill="#000" opacity=".201" cx="20" cy="20" r="20"/><path d="M52.936 24.11c1.942 0 3.517 1.542 3.517 3.445 0 1.903-1.575 3.445-3.517 3.445s-3.516-1.542-3.516-3.445c0-1.903 1.574-3.445 3.516-3.445zm-21.957 0c1.942 0 3.517 1.542 3.517 3.445 0 1.903-1.575 3.445-3.517 3.445s-3.516-1.542-3.516-3.445c0-1.903 1.574-3.445 3.516-3.445zm6.948-4.848v1.429c0 .716.61 1.293 1.348 1.259a1.295 1.295 0 001.225-1.295v-1.393h8.256l13.483 1.313c.956.093 1.676.881 1.676 1.814 0 2.89-2.126 5.303-4.926 5.819.397-3.557-2.458-6.62-6.053-6.62-3.646 0-6.504 3.14-6.039 6.723h-9.879c.466-3.588-2.397-6.722-6.039-6.722-3.595 0-6.45 3.062-6.052 6.62-2.14-.398-3.916-1.912-4.61-3.931h1.142c.731 0 1.32-.598 1.285-1.322-.033-.678-.629-1.2-1.322-1.2H20v-.251c0-1.274 1.066-2.243 2.306-2.243h15.62zM42.59 11c2.645 0 4.99 1.556 5.972 3.963l.726 1.779H40.17L38.413 11h4.178zm-6.865 0l1.758 5.741H26.505l3.357-3.654A6.502 6.502 0 0134.644 11h1.082z" fill="#FFD473" fill-rule="nonzero"/></g></svg>
            <h1 class="title">SEDANS</h1>
            <p class="text">Choose a sedan for its affordability and excellent fuel economy. Ideal for cruising in the city or on your next road trip.</p>
            <button class="learn-more">Learn More</button>
        </div>
    </div>
</template>

<script>

</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Big+Shoulders+Display:wght@100..900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Lexend+Deca:wght@100..900&display=swap');

    #sedan-frame {
        background-color: #E28625;
        height: 419px;
        display: flex;
        justify-content: center;
        align-items: center;
        width: 327px;
        border-top-left-radius: 2%;
        border-top-right-radius: 2%;
    }

    .flex {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        justify-content: center;
        width: 231px;
        height: 100%;
    }

    .icon {
       text-align: left;
       margin-top: 0px;
    }

    .title {
        font-family: "Big Shoulders Display", sans-serif;
        color: #F2F2F2;
        font-size: 40px;
        font-weight: bold;
        line-height: auto;
        text-align: left;
        margin-top: 3%;
    }

    .text {
        font-size: 15px;
        line-height: 25px;
        text-align: left;
        color: #FFFFFF;
        font-family: "Lexend Deca", sans-serif;
        font-weight: 300;
    }

    .learn-more {
        color: #E28625;
        background-color: #F2F2F2;
        width: 146px;
        height: 45.6px;
        border: none;
        border-radius: 25px;
    }
</style>
