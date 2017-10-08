# GolangSortingVisualization

[![Coverage Status](https://coveralls.io/repos/SimonWaldherr/GolangSortingVisualization/badge.png)](https://coveralls.io/r/SimonWaldherr/GolangSortingVisualization) 
[![Build Status](https://travis-ci.org/SimonWaldherr/GolangSortingVisualization.svg?branch=master)](https://travis-ci.org/SimonWaldherr/GolangSortingVisualization) 
[![Flattr donate button](https://raw.github.com/balupton/flattr-buttons/master/badge-89x18.gif)](https://flattr.com/submit/auto?user_id=SimonWaldherr&url=http%3A%2F%2Fgithub.com%2FSimonWaldherr%2FGolangSortingVisualization "Donate monthly to this project using Flattr")

this sorting visualization is not intended to recommend any algorithm, if you need a recommendation go [somewhere else](https://en.wikipedia.org/wiki/Sorting_algorithm#Comparison_of_algorithms).

## Sorting Algorithms

### BogoSort

[![Bogo Sort Animation](http://simonwaldherr.github.io/GolangSortingVisualization/sort_bogo.gif)](https://en.wikipedia.org/wiki/Bogosort) 

### BubbleSort

[![Bubble Sort Animation](http://simonwaldherr.github.io/GolangSortingVisualization/sort_bubble.gif)](https://en.wikipedia.org/wiki/Bubble_sort) 

### CocktailSort

[![Cocktail Sort Animation](http://simonwaldherr.github.io/GolangSortingVisualization/sort_cocktail.gif)](https://en.wikipedia.org/wiki/Cocktail_shaker_sort) 

### CombSort

[![Comb Sort Animation](http://simonwaldherr.github.io/GolangSortingVisualization/sort_comb.gif)](https://en.wikipedia.org/wiki/Comb_sort) 

### CountingSort

[![Counting Sort Animation](http://simonwaldherr.github.io/GolangSortingVisualization/sort_counting.gif)](https://en.wikipedia.org/wiki/Counting_sort)

### GnomeSort

[![Gnome Sort Animation](http://simonwaldherr.github.io/GolangSortingVisualization/sort_gnome.gif)](https://en.wikipedia.org/wiki/Gnome_sort)

### InsertionSort

[![Insertion Sort Animation](http://simonwaldherr.github.io/GolangSortingVisualization/sort_insertion.gif)](https://en.wikipedia.org/wiki/Insertion_sort)

### OddEvenSort

[![OddEven Sort Animation](http://simonwaldherr.github.io/GolangSortingVisualization/sort_oddEven.gif)](https://en.wikipedia.org/wiki/Odd–even_sort)

### SelectionSort

[![Selection Sort Animation](http://simonwaldherr.github.io/GolangSortingVisualization/sort_selection.gif)](https://en.wikipedia.org/wiki/Selection_sort)

### StoogeSort

[![Stooge Sort Animation](http://simonwaldherr.github.io/GolangSortingVisualization/sort_stooge.gif)](https://en.wikipedia.org/wiki/Stooge_sort)

## HowTo

```sh
./start.sh
```

```sh
$ go run gsv.go --help
Usage of gsv:
  -algo="bubble": Select sorting algorithm all/bogo/[bubble]/comb/counting/gnome/insertion/oddEven/selection/sleep
  -count=30: number of values
  -fps=10: frames per second
  -max=9: highest value
  -mode=1: visualization mode
  -vis="stdout": Select output: [stdout]/gif
```

## License

[MIT](https://github.com/SimonWaldherr/GolangSortingVisualization/blob/master/LICENSE)