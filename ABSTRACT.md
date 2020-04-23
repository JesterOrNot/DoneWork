The end goal is to fully automate the process of doing math homework. It should go through the following phases

1. Get picture -- The end user scans a photo of the worksheet
2. Transform -- The program transforms the image into a pdf file of all of the words using OCR. And possibly store metadata such as text position (if that is even possible)
3. Get equations -- Using regular expressions the program should identify equations and the type. into an array.
4. Solve -- Solve all equations in equations
5. Rewrite -- Using the metadata captured in step 2 write the solutions to the pdf some distance beneath the question
6. Print -- After everything the program should prompt the user to print or saved the completed homewrok.
