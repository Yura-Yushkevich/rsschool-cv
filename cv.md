Yury Yushkevich
----------------

### Personal information

![alt text][Photo]

[Photo]: myPhotoX150.jpg "Photo"

**Name**: Yury Yushkevich  
**Address**: 22 Lenina Street, apt. 25, Minsk, 220101, Belarus  
**Phone number (Viber, Telegram)**: +375293226787  
**Marital status**: married  
**Date of birth**: 15th August 1981  
**Email**: yura.yushkevich@gmail.com

### Objective

**Developer.**  
 I am interested in finding employment in a company where I can develop software. I like this job and I am sure that a programmer will never be out of work. The range of his activities is unimaginably wide. It is needed everywhere, in any modern production. With such a choice, you can not stay out of business.

### Education

 **Academy of MIA**      
 August 1998 — July 2002      
 lawyer-jurist      
 **Belarusian National Technological University**      
 February 2012 — August 2013      
 "Web design and computer graphics", qualification programmer-Web designer

### Qualifications

 **October-December 2008** TSOT CJSC Belhard - " programming in the C language»  
 **August – October 2013** Artox Digital Marketing School – " SEO specialist»

### Level of English

А2

### Work experience

 **August 2013 – till now** Working for an individual entrepreneur as an html coder

### Software tools used

 Software | Relatively | Quantity | Well | Excellent
:-------- |:-----:| :-------: |:-------: | -------: |
PHP (OOP), MySQL, HTML, CSS, GULP, SASS  |  |  | + |  |
Git, API, javaScript, React, Babel, Webpack  |  | + |  |  |
LAMP, OpenServer  |  |  | + |  |
Windows  |  |  | + |  |
Linux  |  | + |  |  |
WMWare, VBox, CISCO, Ilo  |  | + |  |  |

### My works

1. Website development and support - [alugros.com](https://alugros.com)  
2. Layout - [clickphone.net](https://clickphone.net)
3. Completion of the site (inserting blocks via WP, additional fields) - [dadaticafe.ru](https://dadaticafe.ru)
4. Support and content content of the site - [dom-koles.by](https://dom-koles.by)
5. Site layout and support-en [payin-payout.net](https://payin-payout.net)
6. Site layout (certain blocks - site header, blog page, internal product pages) - [europianosnaples.com](https://europianosnaples.com)
7. Site layout, content filling (certain blocks-reviews, footer) - [ferico.by](https://ferico.by)
8. Layout of site templates - [flw24.ru](https://flw24.ru)
9. Minor improvements to the site, content filling - [tk-pozitron.ru](https://tk-pozitron.ru)
10. Layout and stretch of the gill (WP) - [wnogresources.com](https://wnogresources.com)
11. Layout correction of errors in the previous layout - [incut.ru](https://incut.ru)
12. Site layout and support - [i-retail.com](https://i-retail.com)
13. Layout - [lightil.ru](https://lightil.ru)
14. Layout - [melannett.ru](https://melannett.ru)
15. Revision error correction, layout of internal Bitrix pages - [mexovoy.ru](https://mexovoy.ru)
16. Layout - [microprivod.ru](https://microprivod.ru)
17. Layout of internal pages - [nycriminallawyers.com](https://nycriminallawyers.com)
18. Layout of the site header - [sindecor.by](https://sindecor.by)
19. Adding and editing site blocks - [taris.ru](https://taris.ru)
20. Layout of information pages delivery and payment - [vsemkarniz.by](https://vsemkarniz.by)
21. Content filling - [gipnorody.ru](https://gipnorody.ru)
22. Layout of the main page, correction of errors on internal pages, site support, content filling - [ninazvereva.ru](https://ninazvereva.ru)
23. Correction of errors on internal pages, site support, content filling - [rasagro.ru](https://rasagro.ru)


### My code

``` 
const getResource = async (url)=>{
    const   res = await fetch(url);
        if(!res.ok){
            throw new Error(`Could not fetch ${url}, status: ${res.status}`);
        }
    const   some = await res.json();
    return some;
}
 getResource('https://jsonplaceholder.typicode.com/posts/10000')
  .then((res) => console.log('Success',res))
  .catch(error=>console.error(error));
```