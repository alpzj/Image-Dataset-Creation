# Image-Dataset-Creation

This project is basically in continuation with the image scraper project. In this project we will create folders for all tags an also remove certain images thar are below some threshold value i.e., creating folders based on tags and saving images in it and deleting folders having images less than the threshold value.

## Thresholding Images

After downloaded the images created folders based on tags and stored their respective images in them,Now coming to the last part of the project i.e., only to keep those folders of images that are having a certain number of images in them or that are having images greater than the threshold number. so we've to check the number of images present in a particular folder and then compare it with the threshold value if it's less than the threshold we'll use shutil to move them to a different folder or simply delete them.
