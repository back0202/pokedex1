# ui
- IndexPage
  - Title
  - Description
  - PokemonList
    - List
      - ListItem
        - Image
        - Name
        - Index
  - ImageWrapper
    - Image 
- DetailPage
  - PokemomInfo
  - TabsWrapper
    - Tabs
      - ListItem
        - TabButton
  - About
    - FlavorText
    - TypeList
      - TypeImage
      - TypeLabel
    - PokedexData
      - Title
      - InfoItemContainer
        - InfoItem
          - InfoItemLabel
          - InfoItemValue
    - Abilities
      - Title
      - List
        - ListItem
          - Label
          - Description
  - Stats
    - Title
    - List
      - ListItem
        - Name
        - Amount
        - GaugeWrapper
          - Gauge
  - Evolution
    - Tilte
    - List
      - EvolutionStage
        - ImageWrapper
          - Image
        - DividerWrapper
          - Text
          - Divider
        - ImageWrapper
          - Image
    - EmptyWrapper
      - Empty
# 알게된점
1. react-router-dom
- createBrowserRouter 사용을 추천하는데 데이터 API에 관심이 없다면 BrowserRouter을 사용하라고 하는데 데이터 api가 무엇을 뜻하는지 아직 모르겠다.
2. text-transfrom
- https://velog.io/@toyo8/text-transform%EB%9E%80
# 고민한점
1. 폴더 구조
- https://velog.io/@toyo8/react-%ED%8F%B4%EB%8D%94-%EA%B5%AC%EC%A1%B0
- 폴더를 나누는 이유는 결국 직관적이여야 찾아 보기 편해서가 아닐까
- 사람마다 다르다 그래서 어떤설로 할지 결론은 아직 못 내렸다.
2. useQueryResult
-  모르겠다.
