
<div>
    <h1>Juliya Topal</h1>
     <div>
        <h2>Student Frontend Developer</h2>
     </div>

 <div>
  <h3>
            Contact information:
  </h3>
        <p> Phone: +38 097 6572925 <br>
            E-mail: Juliya.topal@gmail.com <br>
            Telegram: @juliyatopal <br>
        </p>

   <h4>I have been working in finance since 2005. Started as an accountant and progressed to the position of
            Financial Director. At the moment I am working on optimizing the accounting process.
   </h4>
   <h3>
     Skills and Proficiency:
   </h3>
<ul>

<li> HTML5, CSS3</li>
     <li> JavaScript Basics</li>
     <li> Git, GitHub</li>
     <li> C#</li>
</ul>

<h3>Code Examples </h3>
 <pre>
 private static void Human()
    {
        int max = 100;
        int min = 0;
        int tries = 0;
        int maxTries = 6;

        Console.WriteLine("Enter the number");
        int number = Convert.ToInt32(Console.ReadLine());
        int lastGues = -1;

        while (lastGues != number && tries < maxTries)
        {
            lastGues = (max + min) / 2;
            Console.WriteLine($"Did you guess this number? L/B or True (T)? {lastGues} ");
            string answer = Console.ReadLine();
            string inputNew = answer.ToUpper();
            if (inputNew == "L")
            {
                max = lastGues;
            }
            else if (inputNew == "B")
            {
                min = lastGues;
            }
            else
            {
                Console.WriteLine($"Спасибо за игру ");
                break;
            }
            tries++;
 </pre>


 <h3>
    Courses:
 </h3>
 <ul>
  <li> Udemy: C# Programming: From Beginner to Expert</li>
  <li> RS Schools Course «JavaScript/Front-end» (in progress)</li>
 </ul>


</div>

