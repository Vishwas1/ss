First let's understand what is **[Linked data](https://www.youtube.com/watch?v=4x_xzT5eF5Q)**

In computing, linked data (often capitalized as Linked Data) is [structured data](./structured-vs-unstructured-data.md) which is interlinked with other data so it becomes more useful through semantic queries.
Linked Data empowers people that publish and use information on the Web. It is a way to create a network of standards-based, machine-readable data across Web sites.  It allows an application to start at one piece of Linked Data, and follow embedded links to other pieces of Linked Data that are hosted on different sites across the Web. 


> **JSON-LD is a lightweight Linked Data format. It is easy for humans to read and write.**

It stands for Javascript Object Notation for Linked Data. 

Example: 

```
{
  "@context": "https://json-ld.org/contexts/person.jsonld",
  "@id": "http://dbpedia.org/resource/John_Lennon",
  "name": "John Lennon",
  "born": "1940-10-09",
  "spouse": "http://dbpedia.org/resource/Cynthia_Lennon"
}
```

References 

- https://json-ld.org/
- https://github.com/search?q=topic%3Ajson-ld-wg+org%3Aw3c&type=Repositories
- https://json-ld.org/playground/
- https://json-ld.org/learn.html
- [What is Linked Data - Video](https://www.youtube.com/watch?v=4x_xzT5eF5Q)
- [What is JSON-LD? - Video](https://www.youtube.com/watch?v=vioCbTo3C-4)
- [JSON-LD: Core Markup - Video](https://www.youtube.com/watch?v=UmvWk_TQ30A)
