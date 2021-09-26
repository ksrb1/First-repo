# First-repo
first,
    double lenght;
    double width;

    double square;
    double triangle;
    double rectangle;
    
    cout << "input length: ";
    cin >> lenght;
    cout << "input width (if square just put 0): ";
    cin >> width;

    square = lenght * lenght;
    triangle = 0.5 * lenght * width;
    rectangle = lenght * width;

    cout << "Area for your square is: " << square << endl << "Area for your traingle is: " << triangle << endl << "Area for your rectangle: " << rectangle;
