h1, h2, h3, h4, h5, h6: su dung cho tieu de
SEO: trong 1 trang co duy nhat 1 the h1
h2 khoi lon, tieu de

thẻ sematic  
header, footer, aside, nav, main,

p: doan dai, span: doan ngan, inline
strong = bold, em = i
the inline:

- do rong bang noi dung no chua.
- Nhieu the thi se nam tren cung 1 hang.
- bị hạn chế về css.  
  block:
- full body, ke thua tu cha.
- nhieu the block nam voi nhau thì xuống hàng dưới  
   class vs id:  
   class: có the trung  
   id chi co 1: anh hưởng đến SEO, css và js.

BEM: Block Element Modifier
Block**Element--modifier  
Block**Element  
Block--modifier  
Element--modifier

Ctrl + D
selector {
property: value;
}
selector:

- tags: p, div, span
- class
- id
  property:
- color
- font-size
- witdth
  colors: named, hex, rgb, rgba
  em: phụ thuộc vào font-size của chính nó hoặc phần tử chứa nó.  
  rem: theo font-size default của thẻ html.

outline ko có border-radius giống border
margin có thể sử dụng số âm. | padding thì ko.
margin-left: auto;
margin-right: auto;  
có tác dùng với thẻ blocks.
margin collapse: block trên margin-bottom: 70px, block dươi margin-top: 30px => lây giá trị nào lơn hơn 70px
(dung 1 margin thoi)
box-sizing:
content-box:
real_width = width + padding-left + padding-right + border-left + border-right.
border-box:
real_width = width include: padding-left + padding-right + border-left + border-right.

inline-block muốn center thì phải bọc div và dùng text-align
image: cover ko bị méo ảnh.
opacity: 0 | display: none | visibility: hidden
chiem dien tich va tuong tac
opacity, visibility: thuong dung lam transition
box-shadow, text-shadow
block cho ra giua dung: margin: 0 auto. inline: text-align: center
shadow inset, outset
co the overide bien css
do uu tien, chay tu duoi len tren code.
tags < class < id < inline < !important
(h1.title > .title)
(x, y, z) -> (tags, class or attribute, id)

- child selector: firts-child != first-of-type, last-child, nth-child(3), first-of-type
  combinator: +, ~,

a[href^="https"]
a[href$=".vn"]
a[href*=".vn"]
div[data-title="value"]{
color: red;
}
p::first-letter{

}
gradient div, text (webkit-background-clip)
box-shadown
transform: scale(), rotation, translate, skew (hinh binh hanh)
before, after: currentColor. tao 1 lop gia phia sau, truoc
image{
filter: greyscale(2)
}
