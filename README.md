# Expo AsyncStorage Large Data Handling Issue

This repository demonstrates a common performance issue encountered when using AsyncStorage in Expo applications to store large amounts of data.  AsyncStorage is not designed for managing extensive datasets, and attempts to do so can lead to app crashes, unexpected behavior, or data corruption.  This example illustrates the problem and provides a solution using a more suitable alternative.

## Problem

Storing large JSON objects or significant amounts of data directly into AsyncStorage can result in unpredictable behavior, including:

* Application crashes
* Slow performance
* Data loss or inconsistency

## Solution

For efficient management of large datasets in Expo, consider alternatives like SQLite, MMKV, or other persistent storage solutions optimized for performance and scalability.  This repository provides an example of migrating to a more appropriate solution. 

## Usage

1. Clone the repository
2. Run `npm install` to install the necessary dependencies (if applicable).
3. Refer to the `bug.js` file for an example demonstrating the problem.
4. The `bugSolution.js` file demonstrates a solution using an alternative data storage method.