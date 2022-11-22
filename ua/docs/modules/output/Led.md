# Світлодіод

<img src="https://docs.retrogadgets.game/api/modules/Led.png" width="200" align="right">

Світлодіод є основним пристроєм виводу, здатним відображати колір. Світло, що випромінює світлодіод, є фізичним і буде освітлювати сусідні модулі та об'єкти в майстерні.

## Властивості

### State - `boolean`
Світлодіод повинен бути увімкнений. Якщо `true`, то світлодіод випромінює світло `Color`. Якщо `false`, то світлодіод не випромінює світло. Початкове значення можна встановити за допомогою інспектора мультитула.

Не випромінювати світло - це все одно, що намагатися випромінювати світло чорним кольором.

### Color - `color`
Світлодіод, буде світитися, коли `State` буде `true`. Це можна встановити програмно в будь-який час. Початкове значення можна встановити за допомогою мультитула.