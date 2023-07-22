<script>
    export let isSharp = false;
    export let note = "C";
    export let octaveGroup = 1;
    export let keyOffset = 1;
</script>

<div class="{isSharp ? "bg-black w-[3rem] h-[10rem] absolute z-10" : "bg-white w-[5rem] h-[18rem] "} border-solid border-black border-2"
style="{isSharp ? `left: ${5 * keyOffset}rem` : ""}">

</div>