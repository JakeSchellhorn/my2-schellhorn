# my2-schellhorn
# Jake Schellhorn
### Bennett Springs
Bennett Springs is a state park in **Lebanon, Missouri**. There is a spring that runs through the park
that is stocked with rainbow and brown trout. I enjoy going to Bennett Springs to relax and **fly fish**
for trout.

---

### 3 things to do at Bennett Springs
1. Fly Fish for Trout
2. Go for a hike
3. Kayak down the Niangua River

### 3 dishes to get at Bennett Springs
* Grilled Trout
* Fried Catfish Dinner
* Steak Dinner

![About Myself](MyStats.md)

---

Below are some sports that I played growing up. These are all sports that I recomend someone tries and how many hours a week I practiced them in high school.
| Sport | Why I recomend it | Avg Hrs Practiced |
| --- | --- | --- |
| Football | promotes teamwork and creates a family of players | 10-15 |
| Basketball | can be played all year round | 6-8 |
| Baseball | teaches hand eye coordination very fundamental heavy | 8-10 |
| Track and Field | promotes cardiovascular health and will help with most other sports | 4-6 |

---

> "Learn from yesterday, live for today, hope for tomorrow. The important thing is to not stop questioning" -  *Albert Eintein* <br>
> "No great discovery was ever made without a bold guess" - *Isaac Newton*

---

> <https://stackoverflow.com/questions/52732453/dynamic-vertical-stripes-in-div-using-css-and-or-sass>
~~~ 
/// Stripe builder
/// @author Kitty Giraudel
/// @param {Direction} $direction - Gradient direction
/// @param {List} $colors - List of colors
/// @output `background-image` if several colors, `background-color` if only one
@mixin stripes($direction, $colors) {
  $length: length($colors);
  
  @if $length > 1 {
    $stripes: ();
    
    @for $i from 1 through $length {
      $stripe: (100% / $length) * ($i - 1);
      
      @if $i > 1 {
        $stripes: append($stripes, nth($colors, $i - 1) $stripe, comma);
      }
      
      $stripes: append($stripes, nth($colors, $i) $stripe, comma);
    }
    
    background-image: linear-gradient($direction, $stripes);
  } @else if $length == 1 {
    background-color: $colors;
  }
}
~~~
<https://css-tricks.com/snippets/sass/striped-gradient-mixin/>