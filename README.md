# e-Hanoi

**e-Hanoi**は、ハノイの塔を通じて世界中の「司祭」と繋がれるゲームです。

> インドのガンジス河の畔のヴァラナシ(ベナレス)に、世界の中心を表すという巨大な寺院がある。
> そこには青銅の板の上に、長さ1キュビット、太さが蜂の体ほどの3本のダイヤモンドの針が立てられている。
> そのうちの1本には、天地創造のときに神が64枚の純金の円盤を大きい円盤から順に重ねて置いた。
> これが「ブラフマーの塔」である。
> 司祭たちはそこで、昼夜を通して円盤を別の柱に移し替えている。
> そして、全ての円盤の移し替えが終わったときに、世界は崩壊し終焉を迎える。
> 
> ──エドゥアール・リュカ

## Repositories

* [Launcher](https://github.com/Lastronauts/e-Hanoi-Launcher)
* [Game](https://github.com/Lastronauts/e-Hanoi-Game)
* [Back](https://github.com/Lastronauts/e-Hanoi-Back)

## Technical Composition

![tech](https://user-images.githubusercontent.com/85730998/163727967-1e5c1996-4002-4e5f-9538-1b3731f99eac.png)


### Launcher

* Rust
  * Tauri: GUI(Back End)
* TypeScript
  * Next: GUI(Front End)
  * React: GUI(Front End)
  * Material-UI: GUI(Front End)
  * firebase: Authentication

### Game

* Rust
  * Bevy: Game Engine
  * grahql_client: GrahQL Client

### Back

* Rust
  * Actix Web: Server
  * Juniper: GraphQL
  * Diesel: PostgreSQL

## Developers

### Launcher

|dino3616|
|:-:|
|[<img src="https://github.com/dino3616.png" width="150px">](https://github.com/dino3616)|

### Game

|PicrossSoldier|dino3616|
|:-:|:-:|
|[<img src="https://github.com/PicrossSoldier.png" width="150px">](https://github.com/PicrossSoldier)|[<img src="https://github.com/dino3616.png" width="150px">](https://github.com/dino3616)|

### Back

|dino3616|
|:-:|
|[<img src="https://github.com/dino3616.png" width="150px">](https://github.com/dino3616)|