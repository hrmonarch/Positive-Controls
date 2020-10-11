Help is needed cleaning up main.tex.
I chose a template in the "baposter" class and ran with it without realizing that it might have been a poor choice for a smaller document.

1. Maybe the document class should be changed. 
2. The rest of the pictures need to be added.  
3. Some picture resizing needs to happen.  
4. Header could be moved farther up and title made smaller to make more room for photos.  
5. Every new page currently needs  
```
  \end{poster}
  \begin{poster}
```
   This is not ideal.

6. The title is also repeated for the start of every page instead of just being able to call a global command from the beginning.
