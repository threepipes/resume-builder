FROM pandoc-letter

RUN mkdir /output
COPY coverletter-builder /app/
WORKDIR /app

CMD ["--template", "template-letter.tex", "letter.md", "-o", "/output/letter.pdf"]
