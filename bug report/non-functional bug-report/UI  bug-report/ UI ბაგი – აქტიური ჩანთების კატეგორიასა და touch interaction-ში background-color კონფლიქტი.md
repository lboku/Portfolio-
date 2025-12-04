__Id:__ FQMP-20

__Title:__  UI ბაგი – აქტიური ჩანთების კატეგორიასა და touch interaction-ში background-color კონფლიქტი

__Steps:__

1. გახსენით ვებ გვერდი: example.com

2. ჩამოსქროლეთ ჩანთების Product slider-მდე

3. დააკვირდით აქტიურ კატეგორიას

4. გადასქროლეთ ჩანთების კატეგორიები სხვა კატეგორიაზე თითის (დაყოვნებით) დადებით.

__Actual result:__

ფიქსირდება ვიზუალური შეცდომა. აქტიური კატეგორის და touch interaction -ის background-color არის #34404e და თითის აწევის შემდეგ ორივეზე რჩება ეს ფერები.

__Expected result:__

თითის აწევის შემდეგ touch interaction -ის   background color უნდა უბრუნდებოდეს საწყის ფერს,რათა მომხმარებელმა შეძლოს არჩეული კატეგორიის დანახვა.

__Enviroment:__

__Prodaction__
 
__Device:__ iphone 16 

__OS:__ IOS 26.0.1

__Browser:__ CHROME V 141

__Frequency:__ 100%

__Severity:__ საშუალო

__Priority:__ დაბალი

__Attachments:__
XXXXX