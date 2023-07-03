<script>
    export let minH = "300px"
</script>
<div class="card flex flex-col justify-center p-10 gap-10 rounded-tr-[40px] rounded-bl-[40px] rounded-tl-3xl rounded-br-lg w-full min-h-[{minH}] overflow-hidden">
    <slot></slot>
</div>

<style>
    .card {
        background: linear-gradient(150deg, rgba(46, 52, 64, 0.6) 4.81%, rgba(94, 129, 172, 0.6) 56.88%, rgba(143, 188, 187, 0.6) 95.1%), #2E3440;
    }
    </style>