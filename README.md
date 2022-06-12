# ES-6-EcmaScript-2015-
--Concept of ES6
  * let & const & var
  * Template String(Template Literal)
  * Arrow Function (Fat arrow Function)
  * Destructuring(Object Destructuring & Array Destructuring)
  * Object Props
  * Arrays in ES6
  * New no Methods
  * New Global Methods
 <br>
  let & const & var =><br>
  * var - var type variable is function scoped variable
  * let & const - let and const type varibles are block-scoped varibale
  * function scope varibale print inside the function scoped area and also block-scoped area.
  * block scoped variable print inside only blocked scoped, we can not print the function scoped ared and throw error- varible undefined
    
    // 1- function scoped
    // function dispVariable(love){
    //     // function scoped
    //     if(love){
    //         //block-scoped 
    //         var fname="Mohd";
    //         var lname="Anish";
            //console.log(fname+" "+lname);
    //     }
        //console.log(fname+" "+lname);
       
    // }

    // dispVariable(true);

    // 2- block scoped
    // function dispVariable(love){
    //     // function scoped
    //     if(love){
    //         //block-scoped 
    //         let fname="Mohd";
    //         let lname="Anish";
           
    //     }
    //     console.log(fname+" "+lname);
       
    // }

    // dispVariable(true);

    //3- block scope variable print with var keyword

    // var fName="Mohd Anish";
    // if(true){
    //     var fName="Neeraj Kumar";
    //     console.log(fName);
    // }
    // console.log(fName);
    /*
    output : Neeraj Kumar
             Neeraj Kumar
    */

     //4- block scope variable print with var keyword

<!--      let fName="Mohd Anish";
    if(true){
        let fName="Neeraj Kumar";
        console.log(fName);
    }
    console.log(fName); -->
    
    // output: Neeraj Kumar
    //         Mohd Anish

  
  
