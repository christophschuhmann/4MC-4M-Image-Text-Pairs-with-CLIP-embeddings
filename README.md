# 4MC-4M-Image-Text-Pairs-with-CLIP-embeddings
I have created a dataset of Image-Text-Pairs by using the cosine similarity of the CLIP embeddings of the image &amp; it's caption derrived from YFCC100M. I have also added the following propabilities from a NSFW detector: 'sexy', 'porn','drawing', 'hentai','neutral'


# Number of Image-Text-pairs: 4264733

Here can you explore a small part of the data: http://gallerytest.christoph-schuhmann.de/photos/index.php?/category/3


Link to the meta-data with CLIP-embeddings: (coming soon)

Link to the meta-data without CLIP-embeddings: https://drive.google.com/file/d/1edNr-GEYz69RWcsSgskNzjtM--Qxepdz/view?usp=sharing



I used | as a seperator for the CSV files. 
They can be read with     
  df = pd.read_csv(csv_file, sep = '|',lineterminator='\n')

The columns of the CSVs are 

columns =['final_caption', 'title', 'text','usertags','url', 'licensename','image_size', 'source', 'quality_level','sexy', 'porn','drawing', 'hentai','neutral', 'clip_embedding_img']) 




All images from YFCC100M are released under a Creative Commons License. More information about the exact license for each image is in the CSVs.

This dataset (arragement of meta-data in the CSV files, not the images or the texts itself) is released by me under the Creative Commons License: Attribution 4.0 International (CC BY 4.0) 
https://creativecommons.org/licenses/by/4.0/


More about me: http://christoph-schuhmann.de/
