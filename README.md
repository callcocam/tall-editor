#TAL EDITOR

#PUBLICAR AS MIGRATIONS, CONFIG E ASSETS

```
... artisan vendor:publish --tag=editor-migrations --force
... artisan vendor:publish --tag=editor --force
... artisan vendor:publish --tag=editor-assets --force

```
#CARREGAR OS ASSETS
```
    <link rel="stylesheet" href="{{ asset('js/vendor/editor/css/editor.css') }}" />

    <script crossorigin src="{{ asset('js/vendor/editor/js/editor.js') }}"></script>

```
