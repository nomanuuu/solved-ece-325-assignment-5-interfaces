Download Link: https://assignmentchef.com/product/solved-ece-325-assignment-5-interfaces
<br>
<table width="661">

 <tbody>

  <tr>

   <td width="661">InterfacesExercise 1

    <table width="285">

     <tbody>

      <tr>

       <td width="70">Comparable</td>

       <td width="79"> interface (</td>

       <td width="136">java.lang.Comparable</td>

      </tr>

     </tbody>

    </table>Java defines a ); this interface is a parameterizedinterface. We will discuss parameterized classes and interfaces in detail later in the course. For now, you do not need to know too much about parameterization — just use it.Read the code in Coffee.java. You are required to complete the class definition to allow collections of coffees to be sorted by the strength.Find the code from CoffeeTest.java. What imports are required to allow it to compile? And how would I rewrite this class to utilize JUnit? Create a JUnit project as submission.Exercise 2Consider the code below. It describes 5 types either classes or interfaces.

    <table width="624">

     <tbody>

      <tr>

       <td width="624">U u; G g; B b; Z z; X x;</td>

      </tr>

     </tbody>

    </table>The following assignments are all legal and compile:

    <table width="624">

     <tbody>

      <tr>

       <td width="624">u = z; x = b; g = u; x = u;</td>

      </tr>

     </tbody>

    </table>However, the following assignments are all illegal and cause compilation errors:</td>

  </tr>

 </tbody>

</table>

<table width="624">

 <tbody>

  <tr>

   <td width="624">u = b; x = g; b = u; z = u; g = x;</td>

  </tr>

 </tbody>

</table>

<table width="187">

 <tbody>

  <tr>

   <td width="50">TreeSet</td>

   <td width="21"> (</td>

   <td width="116">java.util.TreeSet</td>

  </tr>

 </tbody>

</table>

<table width="50">

 <tbody>

  <tr>

   <td width="50">runTest</td>

  </tr>

 </tbody>

</table>

<table width="44">

 <tbody>

  <tr>

   <td width="44">Person</td>

  </tr>

 </tbody>

</table>

<table width="70">

 <tbody>

  <tr>

   <td width="12"> </td>

   <td width="44">Person</td>

   <td width="14">)</td>

  </tr>

  <tr>

   <td colspan="3" width="70">Comparator</td>

  </tr>

 </tbody>

</table>

<table width="70">

 <tbody>

  <tr>

   <td width="70">Comparator</td>

  </tr>

 </tbody>

</table>

What can you state about the types and their relationships (to each other)? Provide at least one possible answer.

<h1>Exercise 3</h1>

The collections library has a class ). It is another parameterised

class which is an example of a sorted set. That is, elements in this set are kept in order. Construct  and PersonCompator to make the  in PersonTest.java successfully

complete. This method checks if Person objects are correctly ordered by their ages (age is the only attribute of PersonComparator is required to implement interface  ( java.util.Comparator ).  is another parameterised interface -parameterization is common in Java.

What imports are required to allow it to compile? And how would I rewrite this class to utilize JUnit?

Create a JUnit project as submission.

Coffee.java

CoffeeTest.java PersonTest.java