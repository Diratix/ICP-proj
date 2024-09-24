<script setup>
    setInterval(() => {
        let date = new Date();
        let time = document.getElementById("time");
        time.innerHTML = `${date.getHours()}:${date.getMinutes().toPrecision(2)}`;
    }, 1000);
</script>

<template>
    <main>
        <div class="header-container">
            <img src="/profile.jpg" width="150px" class="image-rounded"/>
            <div class="greeting">
                Hi, <br/>
                Im Daniel.
            </div>
            <div style="width: 400px;"></div>
            <div id="time">
                
            </div>
        </div>
    </main>
</template>