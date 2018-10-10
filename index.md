# Call for Papers

## Overview

Using functional programming language constructs in mainstream Object-Oriented languages is becoming increasingly pervasive. For example, developers can now use lambdas, stream, and MapReduce-style computations in languages such as Java, C\#, F\# and Scala, to name a few. Through these mechanisms, developers can declaratively process native data structure like collections and infinite data structures. Streaming Application Programmer Interfaces (APIs), for instance, available in many mainstream Object-Oriented (OO) programming languages, support this paradigm fusing. Other mechanisms include lambdas, i.e., (typically stateless) first-class computational units facilitating deferred execution, and option types, i.e., nomadic types supporting MapReduce-style operations.

These language features have many benefits, including succinct and nearly effortless (syntax-wise) parallelism. However, combining the paradigms may result in code that behaves in ways not expected by developers. For instance, unexpected errors and suboptimal performance may be incurred as subtle considerations are required to produce code that is correct, optimally parallelizable, efficient, reliable, and free of bugs related to nontermination, nondeterminism, and mismanaged resource cleanup in using these constructs. Developers may also not prefer to use these constructs to write concurrent code, perhaps missing opportunities where this modern technology may be beneficial. And, API developers may be restricted in writing libraries that are maximally usable and extendable due to current language design.

One significant problem is that MapReduce is traditionally highly distributed with no shared memory, whereas streaming APIs in mainstream OO languages execute within a single node under multiple threads sharing the same memory. This difference makes using these constructs and APIs prone to such problems as thread contention, necessitating great care in writing correct yet efficient code. Moreover, discovering and repairing these problems may involve complex interprocedural whole-program analysis, a thorough understanding of construct intricacies, and detailed knowledge of situational API replacements. Manually detecting problematic code areas (smells) and uncovering appropriate optimizations that transform source code while preserving its original semantics (refactoring) can be daunting, especially in large and complex projects or when developers are unfamiliar with how best to use such constructs and APIs.

The 1st International Workshop on Functional-inspired Language Features in Mainstream Object-Oriented Programming Languages (FOOPL) aims to bring together researchers, practitioners, and educators interested in this emerging topic with the goal of sharing results and ideas in solving crucial problems in the mass adaptation, correct usage, education, language and API design and implementation, and tool support of functional-inspired language constructs in mainstream OO languages. The workshop will also cover a broader view of this technology by incorporating additional artifacts beyond code, including requirements, specification, and tests for this new paradigm. Researchers, practitioners, and educators will be encouraged to engage in thought-provoking discussions surrounding these topics so that this relatively new technology has the best support for success. The workshop will also provide a productive and constructive setting for cross-boundary collaboration.

## Topics

Topics of interest include, but are not limited to:

-   Design and implementation of functional-inspired language and streaming APIs in mainstream Object-Oriented languages.
-   Extensibility of streaming APIs and functional-inspired language features and constructs.
-   Empirical results on how developers (expect to) use current streaming APIs and lambdas in mainstream OO languages.
-   Assessing upcoming language features and APIs.
-   Issues arising from the interplay of functional and mainstream OO paradigms.
-   Refactoring, migrating, and re-engineering of mainstream OO systems to make use of functional-inspired language features.
-   Using functional language constructs in other software engineering artifacts and activities such as requirements, documentation, and specification.
-   Bug and suboptimal performance detection in the (mis)use of streaming APIs and lambdas.
-   Quality metrics for assessing functional-inspired language features or streaming API usability in mainstream OO software (API and language engineer perspective).
-   Quality metrics for assessing the actual usage of functional-inspired language features or streaming APIs (API and language consumer perspective).
-   Automated repair of programs that use streaming APIs, lambdas, or other function-inspired constructs or APIs.
-   Automated testing of mainstream OO programs using functional-inspired constructs.
-   Using streaming APIs and lambdas in Computer Science education.
-   Concurrency using streaming APIs and lambdas.
-   Static analyses for programs using functional-inspired features in OO languages.
-   Run-time support for improving the efficiency of streaming APIs.
-   Identification of open challenges and proposed solutions.
-   Synergies between streaming API/ functional-inspired mainstream OO programming language research challenges and other research areas.

## Submission Information

FOOPL 2018 invites contributions in the form of papers that are no more than **4 pages** in length. Submissions can stem from either academia or industry. We also welcome industrial and educational talk abstracts. Research papers, practice papers, position papers, and experience reports are all welcomed. All submissions should describe unpublished work and must have been neither previously accepted for publication nor concurrently submitted for review in another journal, book, conference, or workshop. Submissions are peer-reviewed and accepted papers will appear in the workshop proceedings.

## Important Dates

Event | Date
--- | ---
**Submissions due** | February 1, 2019
**Notification:**  | March 1, 2019
**Camera-ready copies due:** | March 15, 2019

## Notes

The official publication date of the workshop proceedings is the date the proceedings are made available in the ACM Library. This date may be up to two weeks prior to the first day of ICSE 2019. The official publication date affects the deadline for any patent filings related to published work.
