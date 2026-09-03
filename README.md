# RatedPizzas

Independent pizza guides organized for scalable city publishing.

## URL model

- Country hub: `/{country}/`
- English city guide: `/{country}/{city}/`
- Localized guide: `/{language}/{country}/{city}/`
- Future restaurant profile: `/{country}/{city}/pizzerias/{restaurant}/`

City source records live in `data/cities/{country}/{city}.json`. A city is published only when its editorial status is `published`; draft records must not enter navigation or sitemaps.

Custom domain: [ratedpizzas.com](https://ratedpizzas.com/)
