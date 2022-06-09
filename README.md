# basic-tags-and-attributes
tags and attributes in html
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>google.html></title><br>
</head>

<body>
   
<br>
<br>
   <a href="https://www.google.com/" target="main">
    <img src="https://tse4.mm.bing.net/th?id=OIP.oVQxMFaSW1BcBdr5Cuv1-AHaEK&pid=Api&P=0&w=276&h=155  " height="143">
   </a>
    <header>
         <pre> EDUCATION      EXPERIENCES     PROJECTS   </pre> 

    </header>

    <main>
        <input type="text" placeholder="Username"> 
        <input type="password" placeholder="password">
      <section><pre>education:  Banasthali vidyapith(btech IT) || Banasthali vidyapith(11-12)  || SRLRC high school Lalgarh(Till 10th)  </pre> </section>
    
    <p>non-semantic tags</p>
      <div>stay curious.Bye bye </div> <!--non-semantic tag(blocked->it takes full space)-->
      <span>goodbye</span>   <!--non-semantic tag(inline ->it takes space till line)-->

    </main>
    <footer>connect with at <br>
        connect with me through email :
        singhxxxxxx@gmail.com <br>
        mobile number:620xxxxxx <br>

    </footer>

    <aside>this is google adds </aside>
   <caption>COUNTRIES</caption>
    <ul>
        <li>india</li>
        <ul>
            <li>STATES</li>
            <ul>
                <li>BIHAR</li>
                <li>UTTARPRADESH</li>
                <li>uttarakhand</li>
                <li>MP</li>
                <li>J&K</li>
                <li>ASSAM</li>
            </ul>
        </ul>
        <li>america</li>
        <li>affrica</li>
        <li>russsia</li>
        <li>england</li>
        <li>dubai</li>
        <li>ukrain</li>
    </ul>
   
    
    <table>
        <caption><b>STUDENT TABLE</b></caption>
       <br>
       <thead>
        <tr>
            <th>NAME</th>
            <TH>stream</TH>
            <TH>graduated with.</TH>
        </tr>
    </thead>
    <tbody>   <!--all the informations are written inside the body -->
        <tr>
            <td>raushani</td>
            <td>science</td>
            <td>Btech</td>
        </tr>
            
        <tr>
            <td>chulbul</td>
            <td>arts</td>
            <td>BA</td>
        </tr>
    </tbody>
        
    </table>


    <table>
        
       <br>
       <thead>
        <tr>
            <th colspan="3">
                INFORMATION </th>

        </tr>
    </thead>
    <tbody>   <!--all the informations are written inside the body -->
        <tr>
            <td>raushani</td>
            <td>science</td>
            <td>Btech</td>
        </tr>
            
        <tr>
            <td>chulbul</td>
            <td>arts</td>
            <td>BA</td>
        </tr>
    </tbody>
        
    </table>
    <button>
        <a href="https://www.google.com/" target="main">Google</a>
    </button>
    <form action="/action.php">
        <input type="file">
         <br>
        <input type="email" placeholder="Enter email address here">

        <p>Q1. which of the following browser you would prefer to choose?</p>
        <label for="100">
        <input type="radio" value="chrome" name="class">chrome
        </label>
         <!--A radio button, allowing a single value to be selected out of multiple choices with the same name value.--> 
        <label for="101">
        <input type="radio" value="microsoft edge" name="class">Microsoft edge <br>
        </label>
        <label for="102">
        <input type="radio" value="safari" name="class">safari
        </label>
        <label for="103">
        <input type="radio" value="firefox" name="class" >firefox
        </label><br><br>
        <h3>Q2. which were your favorite subject in first semester?</h3>
        <label for="engineering drawing">
         <input type="checkbox" value="engineering drawing" name="subject" id="104">engineering drawing 
        </label><br>
        <img src="https://tse3.mm.bing.net/th?id=OIP.WsjnLiugk0bBluWfQ0h3QwHaE8&pid=Api&P=0&w=239&h=159" alt="ED" HEIGHT="50" ><BR>
        <label for="electronics">
        <input type="checkbox" value="electronics" name="subject" id="105">electronics <br>
        <img src="https://tse4.mm.bing.net/th?id=OIP.W_F-1acIvD1w_lx1jL6bBgHaEo&pid=Api&P=0&w=291&h=182" alt="electronics" height="50"> <br>
        </label>
        <label for="computer science">
        <input type="checkbox" value="computer science" name="subject" id="101">computer science <br>
        </label>
        <img src="https://tse4.mm.bing.net/th?id=OIP.2Y0B9iqNwcbQCL27oJgmAwHaEK&pid=Api&P=0&w=323&h=182" alt="cs" height="50"> <br>
        <label for="AutoCAD">
        <input type="checkbox" value="AutoCAD" name=" subject" id="102" >AutoCAD <br>
        </label>
        <img src="https://tse3.mm.bing.net/th?id=OIP.4Y5HwSw-QzIm7tKuhJARTgHaE2&pid=Api&P=0&w=269&h=176" alt="autocad" height="50" > <br>
        <label for="mechanical">
        <input type="checkbox" value="mechanical" name="subject" id="103">mechanical <br>
        </label>
        <img src="https://tse4.mm.bing.net/th?id=OIP.c6Hb204RbwzXTTZ5in8ApwHaEK&pid=Api&P=0&w=272&h=153" alt="mechanical" height="50"><br>
        <br>
        <h3>enter your city</h3>
       <select name="city" id="107">
           <option value="delhi">delhi</option>
           <option value="mumbai">mumbai</option>
           <option value="muzaffarpur">muzaffarpur</option>
           <option value="bangalore">bangalore</option>
       </select>
    </form>
    <h3>Enter you field of interest.</h3>
    <select name="interest" id="109">
        <option value="IT">information technology</option>
        <option value="CS">computer science</option>
        <option value="EC">electronic communication</option>
        <option value="EE">electrical engineering</option>
        <option value="BT">biotechnology</option>
        <option value="MT">mechatronics</option>
    </select><br><br>
    <textarea name="feedback" id="110" cols="50" rows="5" placeholder="feedback">Its amazing.</textarea><br>

    <iframe width="600" height="400"  src="https://www.youtube.com/embed/HcOc7P5BMi4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br><br>
     <br><br><br>
    <iframe height="300" width="600" src="https://www.wikipedia.org/" frameborder="0">wikipedia</iframe>
   <br><br><br>
    <video src="myvideo.mp4" height=" 300" width="600" controls >screen recording</video>
<!--avoid use of loop after controls-->
</body>
</html>
