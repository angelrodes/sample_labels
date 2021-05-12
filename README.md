# Laboratory labels

*Ángel Rodés, 2021*

This is a LaTeX template that generates a PDF file for the samples listed in ```sample_list.txt``` within the groups described in ```groups_list.txt```.

## Template

The template ```labels_5x16.tex``` fits a A4 sheets with 80 labels like this:

![image](https://user-images.githubusercontent.com/53089531/118029012-a1083e80-b35b-11eb-9136-9a15ff4dfd69.png)

But the header of the file can be easily changed to fit any other label distribution.

## How to use

1. Copy your sample list to ```sample_list.txt``` and modify ```groups_list.txt``` to fit the set of labels you need.
Each line will be a sample name or process. The lines will be interpreted in LaTeX, so avoid using symbols like ```_```, ```\```, or ```$``` unless you **want** them to be intepreted.
2. Run the ```.tex``` file in LaTeX. (e.g. ```pdflatex labels_5x16.tex```)
3. Print the generated PDF file. **At the printer dialog: select "no scaling" and/or "ignore margins" for the PDF to fit your labels!**

## Output

The PDF generated should look like this:

![image](https://user-images.githubusercontent.com/53089531/118030199-e1b48780-b35c-11eb-9401-72c18b107307.png)
