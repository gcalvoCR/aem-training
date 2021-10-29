# Important links

- [archetype](https://github.com/adobe/aem-project-archetype.git)


## Important commands

To start archetype
```sh
mvn -B archetype:generate \
-D archetypeGroupId=com.adobe.aem \
-D archetypeArtifactId=aem-project-archetype \
-D archetypeVersion=30 \
-D appTitle="My Site" \
-D appId="mysite" \
-D groupId="com.mysite"
```

To build wknd site 
```
mvn clean install -PautoInstallSinglePackage
```

## Prerequisites to start using AEM
- adobe-public profile

## Project

- core - Java Code, primarily back-end developers.
- ui.frontend - Contains source code for CSS, JavaScript, Sass, Type Script, primarily for front-end developers.
- ui.apps - Contains component and dialog definitions, embeds compiled CSS and JavaScript as client libraries.
- ui.content - contains structural content and configurations like editable templates, metadata schemas (/content,%20/conf?lang=en).


# Topics to learn
- Component basics
  - 