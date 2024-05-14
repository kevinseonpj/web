<div class="justify-center flex items-center h-screen">
    <div class="text-center">
        <h1 class="text-8xl font-bold mb-4 animate-gradient bg-clip-text text-transparent">Hi!</h1>
        <p class="text-md animate-gradient bg-clip-text text-transparent">
            This website is down for now :3
        </p>
    </div>
</div>

<style>
    @keyframes gradient {
        0% {
            background-position: 0% 50%;
        }
        50% {
            background-position: 100% 50%;
        }
        100% {
            background-position: 0% 50%;
        }
    }

    .animate-gradient {
        background-image: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
        background-size: 400% 400%;
        animation: gradient 7s linear infinite;
    }
</style>