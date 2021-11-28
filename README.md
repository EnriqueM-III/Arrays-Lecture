# Arrays-Lecture


## Months
    #include <iostream>
    using namespace std;

    int main()
    {
    
	string month [12] = 
	{ "Jan", "Feb", "Mar", "Apr", "May", "Jun", 
		"Jul", "Aug", "Sep", "Oct", "Nov", "Dec" };

	for (int i = 0; i < 12; i++) {
		cout << month[i] << endl;
	}

## Heartrate
    #include <iostream>
    using namespace std;

    int main()
    {
	
	int heartRates[8] = { 54, 60 ,71 ,59, 62, 63, 60, 58};

	cout << heartRates[3] << endl;
	cout << heartRates[6] << endl;
  
## Heartrate 2
    #include <iostream>
    using namespace std;

    int main()
    {

	int heartRates[8] = { 54, 60 ,71 ,59, 62, 63, 60, 58 };

	for (int i = 0; i < 8; i++) {
		cout << heartRates[i] << endl;
	}

## 5 Subjects
    #include <iostream>
    using namespace std;

    int main()
    {


	int sum = 0;
	int score[5];
	cout << "Enter score for 5 subjects:" << endl;

	for (int i = 0; i < 5; i++) {
		cin >> score[i];
		sum += score[i];
	}


	cout << "The sum is " << endl;
	cout << sum << " The average is " << sum / 5 << endl;


	
}
