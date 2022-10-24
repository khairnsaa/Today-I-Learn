# Today-I-Learn

Today i learn in LearningX - Sparta Coding Club Bootcamp

## SPA VS MPA
The difference between SPA and MPA is that MPAs secure each page to its core. it takes more timee and effort to maintain the security, hence, it will take more time to loading the page.

SPAs secure endpoints faster, but the security level is low. SPAs generally rely in javascripts. This makes them vulnerable to being attacked by cybercriminals because of the data not being compiled for security. SPAs are considered more “modern” and attuned to today’s agile development needs.

However, this doesn’t mean that MPAs don’t work out. Amazon is an MPA and this effectively means that whenever you request new content, the page has to reload all over again. this is considered conventional architecture, but i’ts still highly valuable and is used with great results.

MPAs are best suited for complex websites that do not require a continuation of approach. For e.g. on amazon you don’t require uour page to stay the same when you want to view a product or category. so if you are thinkong of building let’s say a very large ecommerce site, then you sould opt for an MPA architecture.

## Array vs Array-Like Object

An object is a non-primitive data type in javascript that we use to store data in a key-value format. The majority of objects in javascript are derived from the Object prototype. There are various object forms in javascript, depending on the acts of accessing and manipulating the properties, expressed as internal methods; As per ECMAScript documentation, an ordinary object requires specific criteria of the default action for the primary internal methods while an exotic object might not have a default action for a few of its internal methods. object is an array like if it satisfies the criteria: index should start at 0, index should be incremented in the same way as that of an array. should have a length property and return a non-negative integer, and it’s value should be equal to the number of integer index keys

Array is a list of numerically indexed values in the order of their entry; In JavaScript, it’s an exotic object which maintains array-index property keys called an element and a non-configurable property called length, and each array is derived from this Array object inheriting all of its properties like push, pop, slice, map, shift, and many more.

the difference between array and array-like object is:
1. the index range of an array-like object is 0≤I≤2^53–1, whereas the index range of an array is 0≤ I <2^32–1
2. an array-like object is not derived from the array.prototype object. therefore, we cannot perform traversing and remodeling operations like push, pop, foreach and many more.
