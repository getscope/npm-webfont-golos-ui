# WebFont Golos UI

Пакет для установки веб-шрифта: Golos UI.

## Установка

Чтобы установить пакет, Вы можете воспользоваться командой в CLI:

```bash 
npm install --save https://github.com/getscope/npm-webfont-golos-ui
```

или в файле `package.json` создать свойство `dependencies` и добавить ссылку на github-репозиторий:

```json 
{
    "dependencies": {
        "@getscope/npm-webfont-golos-ui": "github:getscope/npm-webfont-golos-ui"
    }
}
```

и выполнить команду в CLI для обновления установленных зависимостей:

```bash 
npm update
```

## Примеры использования и подключения

```css 
body {
    font-family: 'Golos UI', sans-serif;
}
```

Для импорта веб-шрифта в SCSS, Вы можете воспользоваться следующими путями:

```scss 
@import "node_modules/@getscope/npm-webfont-golos-ui/src/scss/_400-normal.scss";
@import "node_modules/@getscope/npm-webfont-golos-ui/src/scss/_500-normal.scss";
@import "node_modules/@getscope/npm-webfont-golos-ui/src/scss/_700-normal.scss";
@import "node_modules/@getscope/npm-webfont-golos-ui/src/scss/_all-normal.scss";
```
