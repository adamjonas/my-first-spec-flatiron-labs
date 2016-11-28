# My First Spec
In this lesson, we'll review the basics of creating a spec in Jasmine and write our first spec.

## Basic Structure
Here is an example outline of a spec suite in Javascript.

```js
import TestSubject from 'testSubject.js';

describe('TestSubject', () => {
  //Declare scoped variables similar to `let` in Rspec
  const a = true;
  
  beforeEach(() => {
    // Test setup for enclosed examples in this scope
  });
  
  afterEach(() => {
    // Test teardown for enclosed examples in this scope
  });
  
  it('passes a simple spec', () => {
    expect(a).toBe(true);
  });
});
```

## Our First Specs
Let's dive right in. First, check out the branch called `js-testing-basic` on the Ironboard repo. There are incomplete specs in `spec/javascripts/learn_v2/models/assessment_spec.js`. Complete the specs by implementating each spec.

Here are some helpful resources:
- [Backbone Model API](http://backbonejs.org/#Model)
- [Jasmine Cheatsheet](https://github.com/snags88/jasmine-cheatsheet)
