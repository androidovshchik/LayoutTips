---
description: У каждого виджета собственная gradle зависимость
---

# AndroidX etc.

#### ViewPager

Это виджет для свайпинга фрагментов \(обычно вместе с табами\). Появился недавно аналог - это `ViewPager2`, но он основан на `RecyclerView`, может строиться как на обычном адаптере, так и на фрагментах. Впринципе я бы предпочел как раз его, если только нет вложенных `RecyclerView`. Долой рекурсию!\)

#### SwipeRefreshLayout

Это стандартное колесико, которое появляется при свайпе вниз для обновления страницы

