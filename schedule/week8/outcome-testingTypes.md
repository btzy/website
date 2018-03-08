%%**Unit Testing:**%%

<panel type="danger" header="`W8.7a` Can explain unit testing :star:" expanded no-close>
<include src="../../book/testing/testingTypes/unitTesting/what/full.md" />
  <panel header=":dart: Evidence" expanded>

Identify some unit tests in AddressBook-Level4 (or your own project).

  </panel>
</panel>

<!-- ==================================================================================================== -->

<panel type="info" header="`W8.7b` Can use stubs to isolate an SUT from its dependencies :star::star::star:" expanded no-close>
<include src="../../book/testing/testingTypes/unitTesting/stubs/full.md" />
  <panel header=":dart: Evidence" expanded>

Identify some tests in AddressBook-Level4,
1. that can be made pure unit tests by introducing stubs
2. that are using stubs to isolate the SUT from its dependencies 

  </panel>
</panel>

<!-- ==================================================================================================== -->

<panel type="success" header="`W8.7c` Can explain dependency injection :star::star::star::star:" expanded no-close>
<include src="../../book/testing/dependencyInjection/what/full.md" />
<!-- TODO: add evidence -->
</panel>

<!-- ==================================================================================================== -->

<panel type="success" header="`W8.7d` Can use dependency injection :star::star::star::star:" expanded no-close>
<include src="../../book/testing/dependencyInjection/how/full.md" />
<!-- TODO: add evidence -->
</panel>

<br><!-- ##################################################################################################### -->

%%**Integration Testing:**%%

<panel type="warning" header="`W8.7e` Can explain integration testing :star::star:" expanded no-close>
  <include src="../../book/testing/testingTypes/integrationTesting/what/full.md" />
  <panel header=":dart: Evidence" expanded>

Explain the difference between unit tests and integration tests. 

  </panel>
</panel>

<!-- ==================================================================================================== -->

<panel type="info" header="`W8.7f` Can do integration testing :star::star::star:" expanded no-close>
  <include src="../../book/testing/testingTypes/integrationTesting/how/full.md" />
  <panel header=":dart: Evidence" expanded>

Use tests from AddressBook-Level4 to illustrate the difference between unit testings and integration testing. Hint: good examples [`seedu.address.storage.StorageManagerTest`](https://github.com/nus-cs2103-AY1718S2/addressbook-level4/blob/master/src/test/java/seedu/address/storage/StorageManagerTest.java),[`seedu.address.logic.commands.AddCommandTest`](https://github.com/nus-cs2103-AY1718S2/addressbook-level4/blob/master/src/test/java/seedu/address/logic/commands/AddCommandTest.java),[`seedu.address.logic.commands.AddCommandIntegrationTest`](https://github.com/nus-cs2103-AY1718S2/addressbook-level4/blob/master/src/test/java/seedu/address/logic/commands/AddCommandIntegrationTest.java)

  </panel>
</panel>
