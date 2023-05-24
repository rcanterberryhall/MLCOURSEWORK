# MLCOURSEWORK

Business Case:

According to https://www.machinemetrics.com/blog/the-real-cost-of-downtime-in-manufacturing, The cost of unplanned downtime due to mechanical machine failure can be as much as $260,000 an hour. Being able to manage machine maintainance, avoiding downtime while also avoiding costly over maintainance is critical to any manufacturing operation. The ability to predict needed mainainance base on real world data rather can prescriptive studies from OEMs would bring huge savings in both time and capital to the manufactoring industry.

Project description:

This project will use the dataset found at https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification as a base to explor the possibilties of using machine leraing techniques as prescribed in the CS 5262 course at Vanderbilt University. The goal is to develop a machine learing based tool that will predict the type of maintainence required based on the data provided from the data set. The data provides the following as state from https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification.

The dataset consists of 10,000 data points stored as rows with 14 features in columns

UID: unique identifier ranging from 1 to 10000
productID: consisting of a letter L, M, or H for low (50% of all products), medium (30%), and high (20%) as product quality variants and a variant-specific serial number.
productID: consisting of a letter L, M, or H for low (50% of all products), medium (30%), and high (20%) as product quality variants and a variant-specific serial number
process temperature [K]: generated using a random walk process normalized to a standard deviation of 1 K, added to the air temperature plus 10 K.
rotational speed [rpm]: calculated from powepower of 2860 W, overlaid with a normally distributed noise
torque [Nm]: torque values are normally distributed around 40 Nm with an Ïƒ = 10 Nm and no negative values.
tool wear [min]: The quality variants H/M/L add 5/3/2 minutes of tool wear to the used tool in the process. and a 'machine failure' label that indicates, whether the machine has failed in this particular data point for any of the following failure modes are true.
This dataset is originally found at https://archive.ics.uci.edu/ml/datasets/AI4I+2020+Predictive+Maintenance+Dataset

Performance metric:

The goal will be to develop a tool that can predict the type of failure with an error rate of less than 25%

Failure modes are:

No Failure

Tool Wear Failure

Thermal Thermal Failure

Power Failure

Overstrain Failure

// Hey Reid, this sounds like you've got your work cut out for you but also got all your ducks in a line. Everything seems well thought out and ready I know you'll hit the 25% error rate without a doubt. No real comments on the README and notebook though, mainly just a few typos here and there. Lines 14 and 15 are the same in the README.md and the failure modes could be more readable with either commas between each or a line break maybe, in markdown to write a line break you put <br_/> but instead of the underscore it's a space.
