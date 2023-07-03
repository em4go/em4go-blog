<script>
    export let minH = "300px"
</script>
<div class="card flex flex-col p-10 gap-10 rounded-tr-[40px] rounded-bl-lg rounded-tl-lg rounded-br-2xl w-full min-h-[{minH}] overflow-hidden">
    <slot></slot>
</div>

<style>
    .card {
        background: radial-gradient(89.08% 66.49% at 81.64% 15.96%, rgba(221, 83, 83, 0.6) 0%, rgba(94, 67, 67, 0.6) 58.12%, rgba(46, 52, 64, 0.6) 100%) /* warning: gradient uses a rotation that is not supported by CSS and may not behave as expected */, #2E3440;
    }
    </style>