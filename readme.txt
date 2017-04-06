# Navigate to the directory containing GISC_NOV2015.md and run the following:

pandoc -t revealjs -s GISC_NOV2015.md -o index.html --css slides.css

# Upload changes to server
cd ..
rsync -av GISC_NOV2015 aubreymoore@guaminsects.net:guaminsects.net/GISC_NOV2015

# Optional: Create a PDF in Beamer style
# pandoc -t beamer --template=default.beamer -s GISC_NOV2015.md -o GISC_NOV2015.pdf
 
