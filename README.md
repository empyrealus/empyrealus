class hello{
  private $greeting;
  private function think_of_correct_greeting($thoughts)
  {
    foreach($thoughts as &$possiblegreeting)
    {
     $possiblegreeting = "Actually... i'm tired.";
    }
    return $possiblegreeting;
  }
  public function gather_greetings($someone_speaking,$tiredmeter)
  {
    if($tiredmeter == 10){return "I feel like a half cooked pasta noodle that didn't make it in the spaghetti bowl.";}else{
      $think_tank = ["Great!","So good I could eat some chips!","Wow, who knew I could feel this great, amazing!"];
      return $this->think_of_correct_greeting($think_tank);
    }
  }
}

$greeting_you = new hello();
$greeting_you->gather_greetings("How are you, @empyrealus!?",10);



- 👋 Hi, I’m @empyrealus it means "vault of heaven."
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
empyrealus/empyrealus is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
