# plantuml-stencils

1. PlantUML用ステンシル
1. カラーセットやよく使うステンシルを管理する
1. 参考にさせていただたリポジトリ
    1. GitHub: Kazuhito00/[PlantUML-ColorSet-Example](https://github.com/Kazuhito00/PlantUML-ColorSet-Example)

## Requirement

1. 使用したいカラーセットを`!include`で取り込む

```
@startuml
!define uml https://raw.githubusercontent.com/flatring/plantuml-stencils/main
!include uml/colorset/ocean-blue.iuml
!include uml/colorset/_skinparams.iuml

Alice -> WhiteRabbit : Hello!
@enduml
```

## Contents

| name            | sequence light                            | sequence dark                            |
| --------------- | ----------------------------------------- | ---------------------------------------- |
| ocean-blue.iuml | ![img](examples/img/ocean-blue-light.png) | ![img](examples/img/ocean-blue-dark.png) |

## Reference

1. [plantuml/plantuml](https://github.com/plantuml/plantuml)
1. [PlantUML official site](https://plantuml.com/)
    1. [日本語](https://plantuml.com/ja/)

## License

1. plantuml-colorset is under [MIT License](LICENSE).
