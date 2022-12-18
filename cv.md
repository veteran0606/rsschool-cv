# Alexander Burnas

## Contact
***Location:*** Kiyv, Ucraine 

***Email:***   [burnasog@gmail.com](burnasog@gmail.com)

***GitHub:***   [veteran0606](https://github.com/veteran0606)

## About me
Hello, my name is Alexander. At the moment i learning *JavaSkript and React*. Befor that i took lesson -*HTML and CSS*-. Also i have sertificate took learning *Java basic level*.
After my studies I want to continue learning React and after that I would like to find a job in some IT company.
## Code Exampel *React*:
```
import Header from './Header';
import Home from './Home';
import About from './About';
import Category from './Category';
import Footer from './Footer';
import CategoryDescription from './CategoryDescription';
import { BrowserRouter as Router, Routes, Route } from 'react-router-dom';
const arr = [{ "title": "/cat/notebook", "body": "РќРѕСѓС‚Р±СѓРєРё" },
{ "title": "/cat/monitor", "body": "РњРѕРЅРёС‚РѕСЂС‹" },
{ "title": "/cat/cellphone", "body": "РњРѕР±РёР»СЊРЅС‹Рµ С‚РµР»РµС„РѕРЅС‹" },
];
const arr1 = [{ "title": "/", "body": "Р“Р»Р°РІРЅР°СЏ" },
{ "title": "/about", "body": "Рћ СЃР°Р№С‚Рµ" },
{ "title": "/cat", "body": "РљР°С‚РµРіРѕСЂРёРё" },
];

function App() {
  return (
    <>
      <Header data={arr1} />
      <Router>
        <Routes>
          <Route exact path="/" element={<Home />} />
          <Route path="/About" element={<About />} />
          <Route exact path="/cat" element={<Category infa={arr} />} />
          <Route path="/cat/:catName" element={<CategoryDescription />} />
        </Routes>
      </Router>
      <Footer />
    </>
  );
}

export default App;
```
## Aducation:   

  **University:**    National Technical University of Ukraine ["Igor Sikorsky Kyiv Polytechnic Institute"](https://kpi.ua/en)  

  **Courses:** JavaScript 2.0 [itgit](https://itgid.info/ru)
## Skills:  
  * HTML5  
  * CSS3  
  * JavaScript  
  * Java basic level
## Languages:
 * Russian native 
 * Ukrainian nativ
 * English A2
