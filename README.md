<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JS2</title>
    <style>
        .hovered {
            background-color: lightseagreen
        }
    </style>
</head>
<body>
    <button id="button">ボタン</button>

    <script>
        // ボタン要素を取得
        var button = document.getElementById("button");

        // マウスがボタン上に乗ったときの処理
        button.addEventListener("mouseover", function() {
            button.classList.add("hovered");
        });

        // マウスがボタンから離れたときの処理
        button.addEventListener("mouseout", function() {
            button.classList.remove("hovered");
        });
    </script>
</body>
</html>
