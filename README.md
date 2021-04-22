# 4M-C-4M-Image-Text-Pairs-with-CLIP-embeddings
I have created a dataset of Image-Text-Pairs by using the cosine similarity of the CLIP embeddings of the image &amp; it's caption derrived from YFCC100M. I have also added propabilities from a NSFW detector &amp; more.

Number of Img-Text-pairs: 4264733


Link to the meta-data with CLIP-embeddings: (coming soon)
Link to the meta-data without CLIP-embeddings: https://drive.google.com/file/d/1edNr-GEYz69RWcsSgskNzjtM--Qxepdz/view?usp=sharing


I used | as a seperator for the CSV files. 
They can be read with     df = pd.read_csv(csv_file, sep = '|',lineterminator='\n')

All images from YFCC100M are released under a Creative Commons License. More information about the exact license for each image is in the CSVs.
