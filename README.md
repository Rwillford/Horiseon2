# Horiseon2

## User Story

AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

## Acceptance Criteria

GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

## My Changes
In no specific order here is a list of everything I changed in the code.

1.Changed the Title from website to Horiseon.
2. Renamed classes: Benefits to benefit. Then I renamed the classes on line 57, 65, 73 to benefits. Renamed classes on line 31, 39, 47 to box. 
3. Added id tag to line 31 to link to nav.
4. Added alt tags to all images, described the picutres but not logo ones. It would seem weird in a screen reader to say gear grinding into money.
5. Fixed line 75 img end tag from ></img> to />
6. After fixing the classes I went through css and consolidated the repetitive and renamed them to there corresponding class. 
7. Changes div class=header to header tag and changes css to match. Also changed out div to nav for ul portion and css to match. 
