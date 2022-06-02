# Instructions:
Evaluate if the tweet is a medical claim. 

Note: A claim is an assertion/declaration that can be checked for its accuracy by consulting appropriate, reliable sources. 
CURE-claims are claims pertaining to prevention/symptoms/research/risk-factors/diagnosis/cure/treatment/healing/therapy for medical conditions.

In this project, we are interested in identifying CURE-claims for medical conditions that are circulated via tweets. Please be advised that this dataset contains unverified and potentially harmful information collected from Twitter. Reader discretion is advised. 

***

## Tweet Annotation Task

Note: A claim is an assertion/declaration that can be checked for its accuracy by consulting appropriate, reliable sources. 
CURE-claims are claims pertaining to prevention/symptoms/research/risk-factors/diagnosis/cure/treatment/healing/therapy for medical conditions 
Answer the following questions for a given tweet: 

### (1) Is the tweet about a medical condition? 

* (a) Yes 
    + (1) they found pre-cancerous polyps today during my procedure that would have become full blown cancer within three years. 
	+ (2) type2 diabetes isn’t “a fat people disease.” it’s an insulin resistance. 
	+ (3) Thirty minutes of exercise can reduce symptoms of depression 

* (b) No 
	+ (1) Lied to students at his sham university, lied to contractors and constructions 	workers, stole from childrens cancer charities, lied to his own political supporters. 
	+ (2) This couple is too sweet...giving me diabetes!! 

### (2) What type of a claim does the tweet contain? 
* (a) Is it a CURE-claim based on personal experience 
A personal claim cannot be checked using publicly-available information or professional fact-checking resources 
    + (1) I was running a fever for five days 
	+ (2) I was placed on a new, for me, monthly medication to control my metastasized cancer. 
	+ (3) I know so many women who ended up with cancer from hormone meds. 
	+ (4) When Rowena found Orlando health cancer institute, the staff provided hands-on guidance and a definitive lung cancer diagnosis, which she'd lacked after months of visits to previous doctors. 

* (b) Is it a quantitative CURE-claim 
Quantitative claims are about: Current value of something, Changing quantity, Comparison or Ranking.
    + (1) 1 in 4 wait longer than 6 weeks to be seen by a counselor for their depression. 
	+ (2) Fat people often get tested at least twice, while thin people get tested maybe once, often 	only if they develop symptoms. more tests - more cases found. 
	+ (3) Diabetic patients who walked regularly outperformed those leading sedentary lives 
	+ (4) Most times, panadol works for mild flu-like symptoms 

* (c) Does the CURE-claim state a correlation or causation or presence/absence of a link? 
    + (1) Research has shown that lsd blotters can be used in microdoses to improve 	mental health. let us fight for the legalization of... 
	+ (2) Tetanus vaccine causes infertility. 
	+ (3) There is no evidence that boiled garlic water can cure coronavirus infection 

* (d) Does the CURE-claim pertain to prediction, hypothesis regarding the future 
    + (1) The inflammation will have reduced by now had she followed the doctor's advice 


* (e) The claim describes current laws or rules of operation, procedures of public institutions, and other declarative sentences, rules and changes related to medical conditions but are non-CURE related 
	+ (1) y'all, let's not forget most ml is not paid. you used accumulated pto to pay for 	one or 2 weeks. there is nothing special about ml aside from being able to begin the bonding 	process with your baby to avoid postpartum depression.... and even then it's not enough 	time. 
	+ (2) EPA moves to ban the most common type of cancer-causing asbestos 
	+ (3) Residents cannot claim COVID Allowance if they have been in the country for less than 6 months... 
	+ (4) The UK was the largest exporter of the vaccine from the Eurozone. 

* (f) OTHER types of claim NOT related to CURE. The tweet may be about voting records, public opinion, support, definitions, or other sentences that do NOT fall under the categories ypes listed above
	+ (1) Public satisfaction with the NHS in Wales is lower than it is in England. 
	+ (2) The company promised free childcare for clinically depressed staff” 
	+ (3) Gestational diabetes in fat people is a prime example of confirmation bias. 
	+ (4) Good nutrition works. onions & garlic have natural antibacterial properties but covid-19 	is a virus. 
	+ (5) Hand washing is NOT the same as hand sanitizer 

* (g) NOT a claim 
Tweets expressing opinions, speculations or other personal/random comments... 
	+ (1) So...Diabetes or Alzheimer's? 
	+ (2) Questions on the Pfizer vaccine 
	+ (3) If you think coronavirus is bad, try my mom's email forwards about coronavirus. 
	+ (4) Garlic may be tasty, but it won't protect you from the new don't spread rumors. 

### (3) If the tweet contains a CURE-claim, do you think the claim is of interest to the public? 
* (a) Yes, the claim has potentially useful or potentially harmful information.
* (b) No, not-a-claim, unimportant, irrelevant claim.

### (4) Do you think the CURE-claim must be professionally factchecked/verified for the mentioned claim? 
* (a) Yes, people interested in the medical condition will benefit from knowing its accuracy.
* (b) No, not-a-claim, unimportant, irrelevant claim.