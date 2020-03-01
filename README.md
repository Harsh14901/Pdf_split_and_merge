# Pdf_split_and_merge
This is a python script to enable you to split your pdf according to your wish and merge any pdfs while you split at the same time.

Gone are the days to upload a pdf file to a 'pdf modifier website' wait for them to make changes and then download it and then you get frustrated when it allows no more that certain number of pdf files or blocks your IP for a certain amount of time. Now avoid all these hassles by directly modifying pdf files right from your command line!

# Usage

Run the python script and enter the file names in the following manner -:

```{input_pdf1.pdf}[i1,i2,...r1-r2,..]  {input_pdf2.pdf}[i1,...r1-r2,..] ...  {output_pdf.pdf}```

Here ```{file.pdf}``` is the path to the pdf file and the terms in the ```[]``` indicate the page numbers of the pdf that you want to split and merge with similarly extracted pages of another pdf to combine into another pdf at the path ```output_pdf.pdf```. All pages within ```[]``` are comma seperated and a single integer ```i``` denotes the page number ```i``` and ```i-j``` denotes the pages from ```[i-j]``` all inclusive.


## Tip

Add ```alias pdfmod='python3 path_to_this_script' ``` in your ```.bashrc``` file to run the python script directly from the terminal. 
