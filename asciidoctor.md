asciidoctor -T ../asciidoctor-deck.js/templates/haml origami-deck.adoc
python -m SimpleHTTPServer
asciidoctor-epub3 -D output data/samples/sample-book.adoc
