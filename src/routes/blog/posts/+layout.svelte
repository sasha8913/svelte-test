<div class="container">
    <a href="/blog" class="linkr">Домой</a>
    <slot />
    <div>
        <style>
            .container {
                max-width: 1320px!important;
                margin: 50px auto!important;
                max-width: 800px;
                padding: 20px;
            }

            .linkr {
                color: rgb(10, 10, 139);
                background: #ff9800;
                padding: 10px;
                border-radius: 10px;
            }
        </style>
    </div>
</div>
