<script>
    export let color_hue;
    export let steps;
    $:actual_value= +color_hue + +steps;
</script>

<div class="border-solid border-4 shadow-2xl w-1/6 h-2/6 rounded-3xl" style="background: linear-gradient(175deg, hsl({actual_value}, 60%,70%) 0%, hsl({actual_value}, 30%,30%) 100% )"></div>