<h1>Estimate</h1>

We estimated that meeting the requirements and making the observer functionality more generic would take 30 hours to complete this project.

<h1>Description</h1>

We are required to make the observer functionality more generic so as to be able to add other types of observers and we are also needed to move the PartObservers to be in a better library location. Instead of relying on CoreSession, we'll most likely require a TopLevel Session class. Then have observers from diverse needs join that top-level Session class. It contains a list of PartObservers, and also required were the various types of Observers.

<h1>Requirements</h1>

1. All core Observer services should be in libcore.
2. Application specific portions of Observer should be in appropriate libraries.
3. A high-level Session object is required. As a result, on CoreSession, application-specific observers are not registered.
4. A second use case for observers needs to be implemented to show that core functionality is isolated but can be extensible.
