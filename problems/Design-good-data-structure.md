# Design good data structre

It is really rather hard problem...

First, it may need some boundary to better define this problem.

In common software development, you can just use a database and a ORM library to help cover most of the dirty work, however, when it comes to some high-performance related work and the demand may be very special, it could need much more thinking on this problem.

Words in the title is a little simple, I will describe the problem more specific.

1. If the demand can not be solved with a simple database and corresponding ORM library, which points should be considered if the the application is data-intensive?

2. If we have already choosed a database, how should we design proper data structure in languages to let the program easy to extend and have high performance at the same time.

3. use just array and matrix, and store them in text files seems not so bad, I have seen some of classmates done similar work related to deep learning(data volume is small here and they do not have complicated dependence on each other)

4. some operation on a set of data should consider about consistency on the structure and it may need to be locked while do some operation, are there any techniques to improve efficiency?

I got this problem while writing a TODO items management software myself, and spent some time thinking how to design a good part for it to manage datas, this app is really a data-centered app. I need these data to be easily operate on(api should be clean and extensible), easily stored(store fast, read fast and cross-platform), easily read(if outputed, it should be readable), easily migrated(it can be stored in many different places)...(may be some more requirements in the future, if I want to add other features to my app)

And I thought designing good data structure can be a really hard problem...I once read an article talking about data structure used in Ethereum project... really complex...

There are also a lot of books talking about related problems, say, a very popular one, [DDIA](https://dataintensive.net/). Going to read it some time in the future, have already bought some books recently but not read them yet... and this book's China distribution is just too heavy... 1.06kg... reminded me the days I carried some of my heaviest books home and back to school... I decided I should complete reading the books already bought first, and buy it later...

In fact I may just use a distributed database and some corresponding ORM frameworks, but as a newbie learning software developing, I think it can be fun to do some experiments on whether or not using database it good enough for this project.(But in fact I thought using a distribued database is a need, it can reduce a lot of work)

Read some tree structure design in git, and I could only say, it is a little complex, but seems better than those in ethereum Project...

In fact, I know all of the above problems can be solved by reading a lot books, I believe there are many books talking about the various specific techniques in building a data intensive application.(In fact, read a little part in chapter 2 of DDIA, and I thoght it is related some of the problems above), and by writing various applications, one can finally get the key points of design good data structures but it seems a really tough way. 

Going to come to this problem regularly and see whether I could solve them some time in the future.

