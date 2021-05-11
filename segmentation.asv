%%
% *To find the Red, Green , Blue objects in the given image using        
% Image Segmentation.* 

%CODE

clc
clear all
close all
warning off

%To load the image.
img=imread(['RGB_OBJECTS.jpg']);
subplot(4,2,1);
imshow(img);
title('Original Image');

%To convert the image to gray scale image.
im1=rgb2gray(img);
subplot(4,2,2);
imshow(im1);
title('Gray Scale Image');

%To find the red colored objects.
red=img(:,:,1);
subplot(4,2,3);
imshow(red);
title('RED Colour Objects');

%To get the segmented image for Red coloured Objects.
final1=imsubtract(red,im1);
fin1=im2bw(final1,0.2);
imwrite(fin1, 'red.jpg');
subplot(4,2,4);
imshow(fin1);
title('Segmented Image');

%To find the green colored objects.
green=img(:,:,2);
subplot(4,2,5);
imshow(green);
title('GREEN Colour Objects');

%To get the segmented image for Green coloured Objects.
final2=imsubtract(green,im1);
fin2=im2bw(final2,0.2);
imwrite(fin2, 'green.jpg');
subplot(4,2,6);
imshow(fin2);
title('Segmented Image');

%To find the blue colored objects.
blue=img(:,:,3);
subplot(4,2,7);
imshow(blue);
title('BLUE Colour Objects');

%To get the segmented image for Blue coloured Objects.
final3=imsubtract(blue,im1);
fin3=im2bw(final3,0.2);
imwrite(fin3, 'blue.jpg');
subplot(4,2,8);
imshow(fin3);
title('Segmented Image');


