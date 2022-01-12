# javascript-basic-interview-question-with-answers-tricy
/*example1 out of the code --------------------------*/  
    <script>
    greetings();
    var greetings = function() {
        console.log("first greeting");
    };
    greetings();
     function greetings() {
        console.log("second greeting");
    };
    var greetings = function() {
        console.log("third greeting");
    };
    greetings();

    </script>
ouput: is 
    second greeting, 
    first greeting,
    third greeting
 /*example2 out of the code--------------------------*/
 <script>
       greetings();
        var greetings = function() {
            console.log("first greeting");
        };
        greetings();
         function greetings() {
            console.log("second greeting");
        };
        greetings();
  ouput: is 
    second greeting,
    first greeting
    first greeting
  /*example3 out of the code--------------------------*/  
  instead we use let or const it will through syntax error 
    greetings();
  let greetings = function() {
      console.log("first greeting");
  };
  greetings();
   function greetings() {
      console.log("second greeting");
  };
  greetings();
  output:
SyntaxError:
