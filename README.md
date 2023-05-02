Download Link: https://assignmentchef.com/product/solved-cosc6000-homework06
<br>
Develop a class called <strong>Weight</strong> that is an abstract data type (ADT) for an weight.

The complete class will include all the following member functions:

A constructor to set pound and ounce; ex. 2lb 12oz can be set as <strong>Weight item1(2,12)</strong>;

If users set the ounce part grater than 15, like <strong>Weight item1(2,20)</strong>, it should be converted to 3lb 4oz.

A constructor to set ounce; ex. 36oz can be set as <strong>Weight item2(36)</strong>; It should be converted to 2lb 4oz.

A default constructor (takes no input) that sets 0lb 0oz.

Public member function, “<strong>get_Pounds()</strong>” that returns the pound part of weight.

Public member function, “<strong>get_Ounces()</strong>” that returns the ounce part of weight.

The return value must be between 0 to 15. Note 16oz=1lb.

Public member function, “<strong>get_Grams()</strong>” that returns the weight in grams.

use 1oz=28.35g

A friend function, “<strong>Weight add(const Weight&amp; w1, const Weight&amp; w1)</strong>”, which adds two <strong>Weight </strong>objects and returns a new object of <strong>Weight</strong> that stores the result.

A friend function, “<strong>comp compare(const Weight&amp; w1, const Weight&amp; w1)</strong>”, which compares two <strong>Weight</strong> objects and returns <strong>comp</strong> type (enum type) variable of:

GREATER if w1&gt;w2, LESS if w1&lt;w2, or EQUAL if w1=w2.

<strong>comp</strong> type is <strong>enum</strong> type defined by

“<strong>enum comp{GREATER=1, LESS=­1,EQAUL=0};</strong>”  see <strong><u>Link</u></strong><strong><u> (http://en.cppreference.com/w/cpp/lan</u></strong><strong>g<u>ua</u>g<u>e/enum)</u></strong>

you may define private member functions. (helper functions)

https://tulane.instructure.com/courses/2165899/assignments/13465091                                                                                                                                   1/2




Output will be:

https://tulane.instructure.com/courses/2165899/assignments/13465091