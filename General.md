## Sorting Types
- Binary Search: Time Complexity: O(log n)
- Linear Search: Time Complexity: O(n)

## Binary Search Tree (BST) & AVL Tree
- Polynomial Time: Generally, polynomial time algorithms have a time complexity of O(n^k), where 'n' is the size of the input and 'k' is a constant.
- Time Complexity: Inserting in BST: Average Time Complexity: O(log n) Worst Case Time Complexity: O(n) (when the tree is unbalanced)
- Time Complexity: Deleting in BST: Average Time Complexity: O(log n) Worst Case Time Complexity: O(n) (when the tree is unbalanced)
- AVL trees are self-balancing binary search trees. Insertion and deletion operations in AVL trees have a time complexity of O(log n).

## Time Complexity of AVL and BST

| Operation   | AVL Tree      | BST (average) | BST (worst)   |
| ----------- | ------------ | ------------- | ------------- |
| Search      | O(log n)      | O(log n)      | O(n)          |
| Insertion   | O(log n)      | O(log n)      | O(n)          |
| Deletion    | O(log n)      | O(log n)      | O(n)          |



## Merkle Tree
- Introduction to Merkle Trees: Merkle trees are hash trees used to efficiently verify the integrity of data stored in large data structures.
- Components of a Merkle Tree:
  - Leaves: Contain hashes of individual data blocks.
  - Internal Nodes: Contain hashes of child nodes.
  - Root Node: Hash of the entire data structure.
- Applications of Merkle Trees:
  - Blockchain: Merkle trees are used in blockchain technology to efficiently verify the integrity of transactions.
  - File Systems: Merkle trees can be used in distributed file systems for data integrity verification.
  - Peer-to-Peer Networks: Merkle trees are employed in peer-to-peer networks to ensure the integrity of data exchanged between peers.
  - Version Control Systems: Some version control systems use Merkle trees to verify the integrity of code repositories.
- Properties of Merkle Trees:
  - Efficiency: Merkle trees allow for efficient verification of data integrity with minimal computational overhead.
  - Security: The security of Merkle trees relies on the cryptographic hash functions used to compute the hashes of individual data blocks.
  - Scalability: Merkle trees can scale to accommodate large datasets while maintaining efficient integrity verification.
- Implementation Considerations:
  - Choosing appropriate hash functions.
  - Handling tree updates efficiently.



## Merkle Tree Applications and Features

| Application | Features |
| ----------- | -------- |
| Decentralized Systems | Merkle Trees are used in decentralized systems such as blockchain to verify the integrity of data. |
| File Systems | Merkle Trees can be used in file systems to efficiently prove the integrity of files. |
| Data Structures | Merkle Trees are a type of data structure that allow for efficient and secure verification of data integrity. |
| Content Addressable Storage | Merkle Trees can be used for content-addressable storage, where data is retrieved based on its content rather than its location. |
| Data Integrity Checking | Merkle Trees can be used for data integrity checking, allowing for efficient and secure verification of data integrity. |






### Quantum startups


# Rugged--points
| Company Name             | 5-year Search Growth | Search Growth Status | Year Founded | Location                | Funding              | What They Do                                                                                                                                                                                                                                                                                                                                                              |
|--------------------------|----------------------|----------------------|--------------|-------------------------|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Qiskit**               | 573%                 | Exploding            | 2017         | Armonk, NY              | Undisclosed          | An open-source platform designed to make quantum computing more accessible to researchers, developers, and businesses. Provides software tools and libraries for programming and simulating quantum computers, as well as access to real quantum devices through IBM's cloud infrastructure.                                                                                                                                 |
| **Q-Ctrl**               | 1,000%               | Exploding            | 2017         | Haymarket, Australia    | $70.8M (Series B)    | Provides tools to improve hardware error, instability, and noise in quantum systems. Focuses on quantum sensing, aerospace, and medical research.                                                                                                                                                                                                                      |
| **PASQAL**               | 1,367%               | Exploding            | 2019         | Palaiseau, France       | $134.6M (Grant)      | Specializes in manufacturing quantum processors. Aims to supply advanced quantum computers.                                                                                                                                                                                                                                                                           |
| **Multiverse Computing** | 350%                 | Regular              | 2019         | San Sebastian, Spain    | $25.3M (Grant)       | Applies quantum computing to traditional finance (TradFi). Develops Singularity, offering quantum-inspired algorithms in a SaaS format with an SDK/toolkit.                                                                                                                                                                                                          |
| **Quantum Machines**     | 100%                 | Regular              | 2018         | Tel Aviv, Israel        | $153M (Series B)     | Develops Quantum Orchestration Platform. Focuses on optimizing hardware-software interaction for large quantum processors.                                                                                                                                                                                                                                            |
| **QC Ware**              | 500%                 | Regular              | 2014         | Palo Alto, California   | $41.4M (Series Unknown) | Provides quantum algorithms to traditional data scientists. Forge, their software, is marketed as turnkey, enabling easy integration with existing workflows.                                                                                                                                                                                                            |
| **Universal Quantum**    | 88%                  | Regular              | 2018         | Brighton, United Kingdom| $14M (Grant)         | Aims to build a million-qubit quantum computer using microwave technology. Focuses on tackling computationally intensive problems.                                                                                                                                                                                                                                      |
| **Zapata Computing**     | 67%                  | Regular              | 2017         | Boston, Massachusetts   | $67.4M (Series B)    | Develops quantum software for various industries. Known for expertise in quantum computing field.                                                                                                                                                                                                                                                                       |
| **Riverlane**            | -17%                 | Regular              | 2017         | Cambridge, United Kingdom | Not provided        | Develops Deltaflow.OS software to optimize quantum computer performance. Focuses on trapped ions as qubits.                                                                                                                                                                                                                                                             |
| **Rigetti Computing**    | 300%                 | Exploding            | 2013         | Berkeley, California    | $190.6M (Series C)   | Builds quantum computers and develops software for practical quantum computing applications.                                                                                                                                                                                                                                                                             |
| **IonQ**                 | 450%                 | Exploding            | 2015         | College Park, Maryland  | $84M (Series D)      | Develops trapped-ion quantum computing hardware and software. Aims to build scalable quantum computers with high-fidelity qubits.                                                                                                                                                                                                                                        |
| **Xanadu**               | 200%                 | Regular              | 2016         | Toronto, Canada         | $41M (Series B)      | Specializes in photonic quantum computing and quantum machine learning. Provides tools for developing quantum algorithms and applications.                                                                                                                                                                                                                              |
| **D-Wave Systems**       | 150%                 | Regular              | 1999         | Burnaby, Canada         | Not provided         | Commercializes quantum annealing computers targeting optimization problems in various industries.                                                                                                                                                                                                                                                                      |
| **Atom Computing**       | 500%                 | Exploding            | 2018         | Berkeley, California    | Not provided         | Develops neutral atom-based quantum computers with a focus on achieving scalable, fault-tolerant quantum computation.                                                                                                                                                                                                                                                     |
| **ColdQuanta**           | 300%                 | Regular              | 2007         | Boulder, Colorado       | $32.4M (Series A)    | Specializes in quantum atomics. Provides hardware and software solutions for quantum computing, simulation, and sensing applications.                                                                                                                                                                                                                                  |
| **Archer Computing**     | 800%                 | Exploding            | 2018         | Sydney, Australia       | Not provided         | Focuses on room-temperature quantum computing technologies for practical applications. Develops quantum computing hardware and software.                                                                                                                                                                                                                                  |
| **Alpine Quantum Technologies** | 150%           | Regular              | 2018         | Innsbruck, Austria      | $12.9M (Series A)    | Develops superconducting quantum computers and quantum sensors. Targets applications in quantum computing, simulation, and metrology.                                                                                                                                                                                                                                    |
| **OneQubit**             | 400%                 | Regular              | 2017         | London, United Kingdom  | Not provided         | Develops quantum software and algorithms for various industries including finance, healthcare, and materials science.                                                                                                                                                                                                                                                     |
| **Qu & Co**              | 600%                 | Exploding            | 2016         | Amsterdam, Netherlands  | Not provided         | Develops quantum algorithms and software tools for quantum computing applications. Focuses on quantum chemistry, optimization, and machine learning.                                                                                                                                                                                                                      |
