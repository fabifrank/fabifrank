# Hi, my name is Fabian (◠﹏◠) 

software & data engineer with passion for data analysis and machine learning.

## Stack

### Web Development

#### Frontend

Started SPA frontend development in 2011 with Backbone JS and soon went to Ember due to its opionated nature in terms of splitting concerns when designing the frontend architecture, but actually soon after React JS and its design principles & ecosystem kicked my mind and still do. From my POV the React JS community did some very great effort in testing & inventing new concepts to make frontend development a breeze while staying flexible. But I also don't want to blame the other frameworks and did some projects in Vue JS and Angular. Vue is a perfect fit when it comes to pocs and small web applications and Angular is good in terms of onboarding people, as it bundles a lot out of the box and people who worked with angular know what to do. What I miss though in angular is modern principles in terms of state management. For example, there have been a lot of efforts in providing ngRX alternatives, but they dont seem to be that accepted by community - thats different in the React space (think about Relay or generally the concept of pure functions without side effects being introduced by state management tools that use global stores).

#### Backend

I really liked the concept of writing code in one language with JavaScript in the beginning cause its easier to build a full stack application but for years I believe thats not entirely "true": the runtime isn't that performant as other compiled binaries running on the server and the JS ecosystem often suffers bugs and versioning issues. Also, without strict TypeScript implementation its horribly easy to write type-unsafe code compared to Go. Some good thing of the interpreted and lazy nature of JS is the abiliy to write unit tests and replace the AST by mocking functions to isolate the test scenario. Some good read on runtime performace for a simple tcp backends: https://www.toptal.com/back-end/server-side-io-performance-node-php-java-go.
For backends that work with data a lot (ETL) I would (almost) always prefer Python as its driven by a huge ecosystem of data related tools (Tensorflow, Scikit, Numpy, Pandas, Keras and its support for spark). Apart from that, my favourite language of choice is Golang for most cases. And the last one: when it comes to security sensitive applications I would vote for Rust although it has some new concepts that are hard to implement in the moves when learning like borrowing - but it introduces a decent amout of more error soures that the RUST compiler can spot which most other popular languages aren't able to.

#### Infrastructure / Operations

Further very interested in integrating & securing services with Kubernetes and its NetworkPolicy, PodSecurityPolicy (to sad that it has been stopped being developed) as well as gRPC/protobuf and message queues like Apache Kafka. Docker is fun for me, especially when aiming to reduce the container & runtime size to the bare minimum with distros like Alpine :)

#### Web 3.0

I really appreciate the work of the ingenious minds at Bitcoin, Ethereum and other successors like Polkadot (🙌) and did some work with distributed technologies (and secure distributed data transfer) which has been successully security audited from cure53. We are currently implementing another protocol in Substrate with Rust due to its small footprint and program stability & performance. So if you are looking for support for your decentralized or even distributed project: drop me an email!

## Contact

I am looking forward to interesting chats about the different technologies, so feel free to touch base at [swift.boat8455@fastmail.com](mailto:swift.boat8455@fastmail.com).

## Worth reading...

### Why to pick ed25519 over RSA keys

"Technical Overview" section: https://cryptsus.com/blog/how-to-secure-your-ssh-server-with-public-key-elliptic-curve-ed25519-crypto.html
