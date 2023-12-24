# Lorem-Ipsum-Text-Generator
Generate random Lorem Ipsum paragraphs.
import lorem

def generate_lorem_ipsum_paragraphs(num_paragraphs):
    for _ in range(num_paragraphs):
        paragraph = lorem.paragraph()
        print(paragraph)
        print("\n")

num_paragraphs = int(input("Enter the number of paragraphs for Lorem Ipsum: "))
generate_lorem_ipsum_paragraphs(num_paragraphs)
