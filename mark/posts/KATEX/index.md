---
date: 2020 - August 29
title: KaTeX
...

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin lobortis vel orci sed auctor. Phasellus eu diam in felis maximus cursus laoreet vel mi. Sed lectus lectus, posuere at vehicula feugiat, facilisis ut est. Maecenas aliquam ligula eget quam hendrerit, vel fringilla ligula condimentum. Praesent ultricies, est eget rutrum sodales, lectus nisl auctor massa, et varius eros nulla et quam. Fusce condimentum quis nibh vitae vestibulum. Sed imperdiet vel sem vel tempus. Ut at consequat arcu. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nulla velit arcu, dictum non arcu quis, semper ullamcorper elit. Nullam ullamcorper in risus nec finibus. Nulla ipsum nunc, pellentesque id tempus ac, efficitur convallis orci. Aliquam consectetur dignissim lectus, non aliquam diam convallis malesuada. Nulla vehicula leo at lectus maximus, a pretium velit viverra. Maecenas suscipit sapien vitae convallis lacinia.

## This is a test

Aenean blandit libero nec nunc laoreet, commodo pulvinar lacus sagittis. Duis euismod erat eu auctor convallis. Donec nec convallis tellus, eu viverra turpis. Donec sagittis nunc sit amet tortor commodo sodales. Sed congue sit amet est sit amet imperdiet. Donec auctor tempus arcu, quis tempor est suscipit sit amet. Nam commodo quis ipsum vitae rutrum. Etiam aliquam nisi arcu, et rutrum turpis dapibus et.

$$
\sum\limits_{n=1}^{\infty} \frac{1}{n}
\; = \;
1 + \frac{1}{2^2} + \frac{1}{3^2} + \cdots
\; = \;
\frac{\pi^2}{6}
$$
$$
\int_{-\infty}^{\infty} \text{e}^{-\frac{x^2}{2}} \text{d}x = \sqrt{\pi}
$$

Quisque aliquet nisl sem. Suspendisse potenti. Maecenas eleifend, lorem quis maximus eleifend, libero enim bibendum nisl, sit amet tristique elit ante ac lectus. Aliquam semper varius sem mattis tincidunt. In hac habitasse platea dictumst. Sed quis mi bibendum, gravida augue auctor, aliquam mi. Praesent vitae libero sit amet libero maximus ullamcorper. Maecenas nec lectus ut arcu ornare maximus nec vel neque. Vestibulum dignissim massa quis magna sagittis elementum. Praesent hendrerit nulla quis eros posuere sodales.

Nunc finibus leo ac velit lacinia, eu condimentum est dapibus. Integer convallis ut turpis nec porta. Cras urna lectus, fermentum eu erat sed, tempor feugiat risus. Suspendisse a diam dolor. Duis sit amet imperdiet neque. Aenean vitae tristique leo, et auctor sem. Nam fermentum mi sed felis lobortis varius. Maecenas blandit nisi id massa consectetur mattis. Vestibulum sit amet consectetur sem. Maecenas sodales eros at arcu ullamcorper dapibus.

```python
def get_dragon_fractal_corners(N: int) -> Generator[bool, None, None]:
    """ Returns iterable of boolean values;
          False <=> Right turn
          True <=> Left turn
    """
    corners = [False]
    for fold in range(1, N+1):
        new_corners = (i % 2 == 0 for i in range(2**fold))
        corners = (c for pair in zip(new_corners, corners) for c in pair)  # interleave
    return corners
```

Cras luctus, tellus eu aliquet facilisis, nunc est consequat velit, vel porta nisi est id nunc. Maecenas massa mi, dignissim a mi at, auctor congue odio. Phasellus sodales nunc in tincidunt accumsan. Aenean est risus, pulvinar vel ante quis, vestibulum blandit nunc. Morbi erat erat, volutpat et blandit vel, consectetur ut quam. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nulla vestibulum tristique nulla, id euismod odio ultrices in. Cras convallis, libero et aliquam luctus, lectus tortor ultricies nunc, ac efficitur nisl est ultrices mi. Fusce vel hendrerit nibh. Proin tempus erat massa, vel vulputate ipsum blandit vitae. Praesent odio neque, tempor eget iaculis vel, mattis non orci. Duis accumsan elementum gravida. Quisque condimentum sed mi vel semper. Cras rhoncus nisi id justo faucibus facilisis.

