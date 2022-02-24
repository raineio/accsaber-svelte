<script lang="ts">
    import LeaderboardPlayer from "./Components/LeaderboardPlayer.svelte";

    let apData;
    apData = 1999
</script>

<main>
    <div class="bg-dark m-3 rounded-3 list-inline-item justify-content-start align-content-center">
        <div class="m-auto">
            <img src="./src/assets/ACC_Clan_Logo_RGB_1.gif" height="50" class="m-2"/>
        </div>
        <div class="m-1 d-inline">
            <p>
                lorem ipsum
            </p>
        </div>
        <div class="">
            <p>
                AP: {apData}
            </p>
        </div>
    </div>
</main>
