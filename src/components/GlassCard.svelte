<script>
    export let width = 'w-10'
    export let heigth = 'h-10'
</script>

<div class="bg-white bg-opacity-10 border-opacity-5 border-white border rounded-sm {width} {heigth} backdrop-blur-[8px] p-1">
    <slot></slot>
</div>