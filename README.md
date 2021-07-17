# Etch-A-Sketch Clone using Javascript
This is a simple etch-a-sketch clone that supports randomized colour patterns and customisable pixel sizes.

# Preview
<p align='center'>
  <img src='https://user-images.githubusercontent.com/81805471/126027630-baa228a9-c575-41ec-90e9-46f10cbf73ef.png' alt='Homepage'/>
</p>
<p align='center'>
  <img src='https://user-images.githubusercontent.com/81805471/126027754-79c93ef6-c777-4e03-ac9e-cc2d2daf97b1.png' alt='Sample'/>
</p>

# Table of Contents
- [Preview](#preview)
- [Usage](#usage)
- [Learning Points](#learning-points)
- [Contribute](#contribute)
  - [Adding new features or fixing bugs](#adding-new-features-or-fixing-bugs)
- [Feedback](#feedback)
- [License](#license)
- [Footer](#footer)

# Usage
Simply head to https://naduhz.github.io/odin-project-etch/ to begin using the app! Alternatively, if you wish to host the project locally and make edits, you may clone the repository by doing:

```shell
cd your-directory-name
git clone https://github.com/naduhz/odin-project-etch.git
```

and launching `index.html`.

[(Back to top)](#table-of-contents)

# Learning Points
There were 5 main takeaways from this project:
1. DOM Manipulation
2. Array.forEach()
3. Event Listeners
4. CSS Grid
5. Scope

DOM Manipulation was rather self-explanatory, but the power to manipulate elements that are highly similar (or in this case, identical) was enhanced using Array.forEach(). I was able to create event listeners quickly for all pixels upon the creation of a grid using this method, and the greatest thing about this is the speed at which the function is executed. This worked well with the slider for determining pixel size, as grids were always being generated as pixel size changed. Perhaps the most shocking feature to me was the fact that while I was using a while loop to delete squares manually when resetting the grid, the grid was still being generated at run-time when utilising the slider, showing how fast Javascript is. It was a good idea to declare functions that I would constantly reuse explicitly in the global scope such that they would always be accessible. As for CSS grid, it became really handy in this case as I was generating a literal grid, which is rather straightforward in the case of CSS grid.

[(Back to top)](#table-of-contents)

# Contribute
Please feel free to make any suggestions, edits or raise issues. Forks and pull requests are always welcome. I am not likely to maintain the code from here on as I have to move on to other projects.

[(Back to top)](#table-of-contents)

## Adding new features or fixing bugs
As mentioned above, I am not likely to maintain the code and as such, if you would like to build on this project, you could always fork or clone this repository.

[(Back to top)](#table-of-contents)

# Feedback
As this was done within a month of learning Javascript, the code is written in a very amateurish manner, so criticism is always appreciated with regard to how I can better write or refactor my code.

[(Back to top)](#table-of-contents)

# License
Project License can be found [here](https://github.com/naduhz/odin-project-etch/blob/main/LICENSE).

[(Back to top)](#table-of-contents)

# Footer
I would like to thank [The Odin Project](https://www.theodinproject.com/) for providing the inspiration for this project.

[(Back to top)](#table-of-contents)
