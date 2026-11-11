# Roteiro Prático – Layout Moderno no Android Studio (Java)

Repositório com os dois projetos do roteiro `Tutorial_LayoutAndroid`:

| Projeto | Conteúdo |
|---|---|
| [`AppModerno/`](AppModerno) | `colors.xml`, `strings.xml`, `themes.xml` (light/night), `dimens.xml`, layout com `ConstraintLayout` + `MaterialCardView` + `MaterialButton`, `MainActivity` em Java |
| [`StreamFlix/`](StreamFlix) | Mini projeto: paleta escura, banner, `RecyclerView` horizontal, `MovieAdapter` e `MainActivity` em Java |

## Como executar
1. Android Studio → **File > Open** → escolha a pasta `AppModerno` ou `StreamFlix`.
2. Aguarde o *Gradle Sync* e rode em um emulador/dispositivo (API 24+).

## Observações
- As imagens `banner.jpg` e `movie1..3.jpg` do `StreamFlix` são *placeholders*; substitua por imagens reais (de preferência WebP) em `res/drawable/`.
- No `item_movie.xml` foi adicionado `xmlns:app`, ausente no roteiro e necessário para os atributos `app:cardCornerRadius` e `app:cardElevation`.
