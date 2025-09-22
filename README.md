# SQL Project- Major-League-Baseball-MLB
# Project Overview
Project Title: Major-League-Baseball-MLB
Level : Advance
Database: maven_advanced_sql
This project has large amount of historical Player data.
This project explores decades of Major League Baseball data using advanced SQL queries. 


# Objectives
The goal is to analyze how player statistics have changed over time and across different teams in the league.

# Table creation
-- Table structure for table `school_details`
CREATE TABLE school_details (
    schoolID VARCHAR(50) PRIMARY KEY,
    name_full VARCHAR(100),
    city VARCHAR(50),
    state VARCHAR(2),
    country VARCHAR(50)
);

--
-- Table structure for table `schools`
--
CREATE TABLE schools (
    playerID VARCHAR(50),
    schoolID VARCHAR(50),
    yearID INT,
    PRIMARY KEY (playerID, schoolID, yearID)
);
