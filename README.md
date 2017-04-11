# JAX-RS-Apr-2017

## REST and JSON
  - [JavaScript and JSON Services - JEE not so much](https://dzone.com/articles/j2ee-dead-long-live-javascript)
  - [JSONPlaceholder - test site](http://jsonplaceholder.typicode.com/)
  - [json.org](http://json.org)
  - [Designing a RESTful Web API](http://blog.luisrei.com/articles/rest.html)
  - [Jackson vs Jettison notations](https://books.google.com/books?id=i2j5oKNkrKEC&pg=PA164&dq=jackson+notation,+jettison+notation,+badgerfish+notation&hl=en&sa=X&ved=0ahUKEwjxs7KI2ZzTAhUMw2MKHSBhBuwQ6AEIJDAA#v=onepage&q=jackson%20notation%2C%20jettison%20notation%2C%20badgerfish%20notation&f=false)
  - [jsonapi.org](http://jsonapi.org/)
  
  ## JAX-RS Documentation
  - [Oracle's JEE 6 Tutorial on JAX-RS](https://docs.oracle.com/cd/E19798-01/821-1841/6nmq2cp1v/index.html)
  - [Oracle's JEE 7 Tutorial on JAX-RS](https://docs.oracle.com/javaee/7/tutorial/jaxrs.htm)
  - [RESTEasy docs](http://resteasy.jboss.org/docs)
  - [What's New in JAX-RS 2.0](https://www.infoq.com/news/2013/06/Whats-New-in-JAX-RS-2.0)
  - [Restful Java With JAX-RS 2.0 (book)](https://www.gitbook.com/book/dennis-xlc/restful-java-with-jax-rs-2-0-2rd-edition/details)
  
  ## JAX-RS Techniques
  - [Using Regular Expressions in Path template variables](http://www.logicbig.com/tutorials/java-ee-tutorial/jax-rs/path-regex-matching/)
  - [Path Segments and Matrix Parameters](http://memorynotfound.com/jaxrs-path-segments-matrix-parameters/)
  - [Streaming Responses](https://dzone.com/articles/jax-rs-streaming-response)
  - [Using Patch](http://kingsfleet.blogspot.be/2014/02/transparent-patch-support-in-jax-rs-20.html)
  - [URIInfo and @Context](https://abhirockzz.wordpress.com/2015/05/03/using-context-in-jax-rs-part-1/)
  - [GenericEntity](http://www.adam-bien.com/roller/abien/entry/jax_rs_returning_a_list)
  - [HATEOAS](https://dzone.com/articles/hypermedia-support-in-jax-rs-20)
    
  ## Lab02.01 Extras
  After completing the lab in the courseware:
  1. Create an Artist class in the com.javatunes.domain package.  Include an id (Long) attribute along with other attributes (you decide). Besure to include equals() and toString() methods.
  2. Update MusicItem, replacing the artist String with the Artist class. 
  3. Update the static block in SearchUtility that creates MusicItem.  Create 2 or 3 Artist objects, assigning them at random.  You will need to update the findByKeyword() method as well.
  
  ## Lab03.01 Extra
  Just make the changes to the Lab02.01 project, rather than creating a new Lab03.01 project like the book says.  This way we still have all the Artist changes.  
  
  ## Lab03.03 Extra
  Make changes to the Lab02.01 project.  You may want to copy in TestRest.java from the Lab03.03 project into Lab02.01.
  You can also see the following site for an example (and just wing it):
  1. [MKYong](http://www.mkyong.com/webservices/jax-rs/restful-java-client-with-jersey-client/)
  
  Use Maven to get the required jars rather than manually adding them.  Add the following to your pom.xml:
  - jersey-client (1.19, not 1.19.3)
  - jackson-jaxrs-json-provider
  
  
  
  
  
