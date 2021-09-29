  /*Mark my  Words*/

	int score{};
	char grade{};

	cout << "Input score to get the grade" << endl;
	cin >> score;

	if (score < 40) {
		grade = 'F';		
	}
	else if ( 40 <= score && score <= 49 )
	{
		grade = 'D';
	}
	else if ( 50 <= score && score <= 59)
	{
		grade = 'C';
	}
	else if ( 60 <= score && score <= 69)
	{
		grade = 'B';
	}
	else if(score >= 70)
	{
		grade = 'A';
	}

	cout << "Grade: " << grade << endl;

	return 0;  




/*Starting a Band*/

    bool musician = 0; //only added this cause in the ppt you said we needed a bool
	string musicianValue{};
	string typeOfIntrument{};

	cout << "Oh hey do you play any instruments? yes or no would be fine" << endl;
	cin >> musicianValue;

	if (musicianValue == "yes"){
		musician = true;
	}
		
	
	if (musician == 1) {
		cout << "Oh cool, what instrument do you play? " << endl;
		cin >> typeOfIntrument;

		if (typeOfIntrument == "guitar") {
			cout << "Oh nice, I really need a guitarist Please join me!!!" << endl;
		}
		else if(typeOfIntrument == ("drum") || typeOfIntrument == ("drums")) {
			cout << "Oh nice, I really need a drummer Please join me!!!" << endl;
		}
		else {
			cout << "Aww I only needed a guitarist or a drummer" << endl;
		}

	}
	else {
		cout << "aww i wanted to start a band" << endl;
		return 0;
	}
	
	
	
/*Killing Time*/

	int minTillArival{};
	int pocketChange{};

	cout << "Oh hey, how much longer till you arrive?" << endl;

	cin >> minTillArival;

	if (minTillArival >= 15) {
		cout << "Might as well kill some time, how much money do i have on me?" << endl;
		cin >> pocketChange;

		if (pocketChange > 5) {
			cout << "Nice! I'll go and buy some coffee with this";

		}
		else {
			cout << "Aww, I'll just go for a stroll around town";
		}

	}
	else {
		cout << " Oh guess I'll just wait for you then";
	}

