<template>
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Vue App</title>
    </head>
    <body>
        <p>你好 你很高兴吗？</p>
    </body>
    </html>
</template>

<script>
    export default {
      name: 'SimplePage',
      props: {
        msg: String
      }
    }
    </script>