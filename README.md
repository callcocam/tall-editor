#TAL EDITOR

#PUBLICAR AS MIGRATIONS, CONFIG E ASSETS

```
... artisan vendor:publish --tag=tall-editor-migrations --force
... artisan vendor:publish --tag=tall-editor --force
... artisan vendor:publish --tag=tall-editor-assets --force

```
#CARREGAR OS ASSETS
```
    <link rel="stylesheet" href="{{ asset('js/vendor/editor/css/editor.css') }}" />

    <script crossorigin src="{{ asset('js/vendor/editor/js/editor.js') }}"></script>

```
