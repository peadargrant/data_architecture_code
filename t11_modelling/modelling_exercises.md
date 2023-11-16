% Modelling exercises

Exercises
=========

1.  Al Wright runs a tool hire company. He keeps a large supply
    of tools. Each tool has a unique ID number, a name and
    a description.

    Each tool can be supplied by more than one distributor. Of course,
    it is also possible for a distributor to supply more than one type
    of tool. Distributors can charge different prices for the same tool.

    Each distributor is given a unique ID. Their name, address and phone
    number are also of interest to Al. Al periodically places orders
    with distributors.

    Al extends credit to all of his customers, each of whom is assigned
    a unique ID. Their names and addresses are also stored.

2.  An employee can work on several projects at the same time. Each
    employee belongs to one department. Each department has one manager.

    Each project has a start date and a finish date and a number of
    employees assigned to it. Some employees are assigned to the project
    for its complete duration, others are assigned for different
    time intervals. One employee is assigned as project manager.
    Projects are identified by a project code.

    Most projects are carried out for a single customer, although there
    are some internal projects for which there is no client. At any one
    time a client may have several projects underway.

3.  Students must study six modules. A student is identified by
    student number. Student name, address and start date are
    also recorded. A module has a unique module number, a name and
    a description. A student’s result for a particular module is
    also recorded.

    Each module is taught by one lecturer. Lecturers may teach more than
    one module. Lecturers are identified by lecturer number. Lecturer
    name and office number are also recorded.

4.  The North Eastern College Technological University runs courses for
    students. Each course consists of various subjects and all students
    enrolled on a particular course must attend all subjects associated
    with that course - there are no electives. The same subject may be
    taught on several courses. Each course has a lecturer assigned as
    course coordinator. A lecturer will be in charge of one course at
    most. There is only one lecturer associated with a subject on a
    particular type of course, a lecturer will teach many subjects.

    The college is divided into several departments, each of which has a
    department head and office. Each lecturer is assigned to
    one department.

    Each subject on each course has exams scheduled three times
    each year. The college stores the date, start time, duration and
    venue for each of these exams. The result that each student achieved
    in each of these exams is also stored. All students who take a
    particular subject sit the same exam in that subject.

% Applied modelling for databases

# Exercise

For each of these scenarios:
1. Construct the E-R model on paper.
2. Diagram the E-R model using GraphViz.
3. Implement your model as tables in the database.
   Implement as strict constraints as you possibly can.

## Scenario 0: task manager

(skip if you understand everything to date!)

Tasks have a due date and description.
Each task is linked to a single project.
Each task may be associated with a single client.
There may be tasks with no client.

## Scenario 1: gift shop

A gift shop chain sells items for a number of suppliers.
They require a database system to correctly reimburse suppliers at the end of each trading period.

Each supplier has a first name, surname and contact e-mail address. 
Each item is supplied by a single supplier, must have a description (unique across shop) and price.
Suppliers are free to change the price of a product at any time.
Each item may have a barcode associated with it that must be unique across the store.

The database will be populated with data from the store's cash register automatically.
Need to accurately record the sale of items in each store - must have the date / time of sale, store location, product, quantity sold and amount charged.

## Scenario X: your own data

Draw up model of a data scenario you have encountered.

