

# Boolean Tests #

### assertTrue(inputVal, errorMsg) ###
Compares a value against boolean TRUE. If values do not match, the provided error message is bubbled up to the UI.

### assertFalse(inputVal, errorMsg) ###
Compares a value against boolean False. If values do not match, the provided error message is bubbled up to the UI.

# Equality Tests #

### assertEquals(inputVal, expectedVal, errorMsg) ###
Compares two values for equality based on both value and type. If values do not match, the provided error message is bubbled up to the UI.

### assertNotEquals(inputVal, expectedVal, errorMsg) ###
Compares two values for inequality based on both value and type. If values do match, the provided error message is bubbled up to the UI.

# Undefined/Null Tests #

### assertUndefinedOrNull(inputVal, errorMsg) ###
Checks to see if the passed value is undefined or null.

### assertNotUndefinedOrNull(inputVal, errorMsg) ###
Checks to see if the passed value is not undefined or null.

# String Tests #

### assertContains(parentString, childString, errorMsg) ###
Checks to see if one string is contained within another.

### assertNotContains(parentString, childString, errorMsg) ###
Checks to see if one string is contained within another.

# Other #

### assertIsGuid(inputVal, errorMsg) ###
Tests an input value to see if it is a GUID. If false, the provided error message is bubbled up to the UI.