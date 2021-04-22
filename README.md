# 4MC-4M-Image-Text-Pairs-with-CLIP-embeddings
I have created a dataset of Image-Text-Pairs by using the cosine similarity of the CLIP embeddings of the image &amp; it's caption derrived from YFCC100M. I have also added the following propabilities from a NSFW detector: 'sexy', 'porn','drawing', 'hentai','neutral'


# Number of Image-Text-pairs: 4264733

Here can you explore a small part of the data: http://gallerytest.christoph-schuhmann.de/photos/index.php?/category/3

# The CSVs include the CLIP-embedding (512 dim vector) of each image. 
This allows e.g. similarity search by calculating the cosine similarity between a give image or text CLIP-embedding and the ones in the dataset, simiilarly to what this website does: https://same.energy/


Link to the meta-data with CLIP-embeddings of the images: 
Part 1: https://drive.google.com/file/d/1-5TElUnISAfLHN-1kzlnZAO5f4mjEN1Z/view?usp=sharing
Part 2: https://drive.google.com/file/d/1-BARa0b7m6ds8Hu_vwipr5JvKYc6EtF7/view?usp=sharing


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
