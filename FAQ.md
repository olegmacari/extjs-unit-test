# How do I add my own unit tests? #

You should create a new JavaScript file and include it via the header of "index.html". Inside your new JavaScript file, you can now add any number of tests.

A unit test can be created via the "Ext.ux.NewUnitTest" method, which takes an object literal as its only parameter. That configuration parameter must contain three members:
  * testName - A string with the name of your test.
  * testGroup - A string representing an organizational group for the test.
  * testFunction - A function to be executed by the program.
```
Ext.ux.NewUnitTest({
    testName: 'Testing the fooBar() method...',
    testGroup: 'my.Namespace or MyGroupName',
    testFunction: function() {
        //add any logic 
        //or assertion methods here
        this.assertTrue(true, 'The value isn't true!');
    }
});
```

See the list of currently-supported [assertion methods](AssertionMethods.md).

Refresh the page in your browser, and your tests should now appear grouped inside the grid according the groups you have defined.