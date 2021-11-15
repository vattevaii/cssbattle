# Battle #1 - Pilot Battle

## #8 - Forking Crazy

[Link to the problem](https://cssbattle.dev/play/8)

![result](./images/8-forking-crazy.png)

- This one really hurt my head.. So damn mysterious...
```html
<div class="a">
<c></c>
<c></c>
<c></c>
<c></c>
<style>
    * {
        background: #6592CF;
        margin: 50 auto
    }

    .a {
        background: #060F55;
        width: 140;
        height: 150;
        border-radius: 0 0 100vw 100vw;
        display: flex;
        justify-content: space-between;
    }

    .a::after {
        content: '';
        position: fixed;
        background: #060F55;
        width: 20;
        height: 100;
        top: 240;
        left: 190
    }

    c {
        display: inline-block;
        width: 20;
        height: 120;
        transform: translateY(-50px);
        border-radius: 100vw;
        background: #060F55;
        margin: 0
    }

    c::after {
        position: absolute;
        content: '';
        left: 20;
        width: 20;
        height: 110;
        border-radius: 100vw;
        background: #6592CF;
    }
```
