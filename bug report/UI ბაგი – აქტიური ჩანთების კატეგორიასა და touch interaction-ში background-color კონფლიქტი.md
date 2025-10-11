id: DRES-187
title: UI ბაგი – აქტიური ჩანთების კატეგორიასა და touch interaction-ში background-color კონფლიქტი

steps:
1. შედით ვებ გვერდზე: https://dressup.ge/ka/ 

2. ჩამოსქროლეთ ჩანთების Product slider-მდე

3. დააკვირდით აქტიურ კატეგორიას

4. გადასქროლეთ ჩანთების კატეგორიები სხვა კატეგორიაზე თითის დაყოვნებით დადებით.

Actual result:
ფიქსირდება ვიზუალური შეცდომა. აქტიური კატეგორის და touch interaction -ის background-color არის #34404e და თითის აწევის შემდეგ ორივეზე რჩება ეს ფერები.

Expected result:
თითის აწევის შემდეგ touch interaction -ის   background color უნდა უბრუნდებოდეს საწყის ფერს,რათა მომხმარებელმა შეძლოს არჩეული კატეგორიის დანახვა.

Enviroment:
 სატესტო.

device: iphone 16, 
OS: IOS 26.0.1 , 
browser: CHROME V 141

meta data:
severity: medium
priority: low

Attachments:
 https://drive.google.com/file/d/1POUHsKHTznz9Hds1QGNXbKQz0XvHErEg/view?usp=drive_link