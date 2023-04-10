# User Page: Devika Torvi

## Introduction

Hi, My name is Devika Torvi and I am a 4th year Bioengineering: Bioinformatics Student. I enjoy learning about new technologies and solving biological problems through programming. My favorite thing about San Diego are the sunsets.

![sunset](https://149361101.v2.pressablecdn.com/wp-content/uploads/2021/02/WindandseaBeachLaJolla-SanDiegoSunsets.jpg)

- **Programming Languages:** C++, Python, Java, C#, R, ~~MATLAB~~
- **Interests:** RNA sequencing, Phylogenetics, Precision Medicine, Regenerative Medicine


## Favorite Quote

> "To define is to limit" - Oscar Wilde

## Code Quote

Here is a snippet of code that outputs the most optimal alignment of two DNA strings using dynamic programming and backtracking.
`def OutputLCS(backtrack, v, w, i, j):
    if i == 0 or j == 0:
        return(v,w)
    if backtrack[i][j] == 'down':
        w = w[0:j] + '-' + w[j:]
        return OutputLCS(backtrack, v, w, i-1, j)
    elif backtrack[i][j] == 'right':
        v = v[0:i] + '-' + v[i:]
        return OutputLCS(backtrack, v, w, i, j-1)
    elif backtrack[i][j] == 'diagonal':
        return OutputLCS(backtrack, v, w, i-1, j-1)
    else:
        return(v[i:], w[j:])
`

## Frequently Used Links  

- [GitHub](https://github.com/)
- [YouTube](https://youtube.com)
- [Stack Overflow](https://stackoverflow.com/)
- [LinkedIn](https://www.linkedin.com/)

## Link to Readme
- [Link to Another Markdown File](./README.md)
  
### Favorite Movies

1. Good Will Hunting
2. Pretty Woman
3. Truman Show

### My Hobbies

- Painting
- Singing
- Writing

## Goals For the Quarter

- [] Get a full time job
- [] Learn to cook ten new meals
- [X] Work on an independent programming project 

Link to the Beginning:
[Introduction](#introduction)