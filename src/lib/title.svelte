<script>
    export let title = "Ninja Gaming"
</script>
<div class="title">
    <img src="/poll_ninja_logo.svg" alt="img">
    <h1>{title}</h1>
  </div>

  <style>
    .title{
        display: flex;

    }
    .title img{
        display: inline-block;
        width: 100px;
        filter: invert(88%) sepia(18%) saturate(886%) hue-rotate(199deg) brightness(100%) contrast(90%);
    }

    .title h1{
        margin-left: 10px;
    }
  </style>