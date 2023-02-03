<script lang="ts">
    let catpath = '/cat.png'
    //let discordpath = 'src/lib/discord.jpg'
    let discordpath = '/discord.png'
</script>

<div class="grid place-content-center w-screen h-screen text-white bg-black">
    <h1 class="">stravabot</h1>
</div>

<div class="grid grid-cols-1 py-16 w-screen">
    <h1 class="pb-16 text-2xl text-center">
        Do you enjoy? strava. Or do you just want to matisse your discord up a bit?
    </h1>
    <div class="grid grid-cols-2 gap-4 px-8 py-4 bg-slate-600">
        <p class="place-self-center">
            Central to the matisse philosiphy is a hate of dogs if you like dogs then you are not
            you like the molasses that grows in windter. Durn it! If matiise is then matisse was and
            if matisse is matisse then what is a dog if not evil?
        </p>

        <img class="place-self-center w-64 h-64 rounded" src={catpath} alt="cat" />
    </div>
    <div class="grid grid-cols-2 gap-4 px-8 py-4 bg-slate-200">
        <img class="place-self-center w-64 h-64 rounded" src={discordpath} alt="sowing discords" />

        <p class="place-self-center">
            Is matisse not enough for you in yuo'er pitiful life? Well Darl has an answer:
            stravabot. You can add it to any discord and, once connected to your account, will post
            all activities in your club to that discord. Yay!
        </p>
    </div>
</div>

<style lang="postcss">
    :global(html) {
        background-color: theme(colors.gray.100);
    }
</style>
