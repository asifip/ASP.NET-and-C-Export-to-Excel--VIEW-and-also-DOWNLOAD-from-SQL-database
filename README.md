# ASP.NET-and-C-Export-to-Excel--VIEW-and-also-DOWNLOAD-from-SQL-database
REQUIRES: VISUAL STUDIO 

Download the zip file.

Extract it.

Double Click the file "NEWPROJECT.sln".

Visual Studio will run this file as a solution. 

After Visual Studio opens: go to Solution Explorer (Left Vertical Side Bar) and Right click the file "WebForm1.aspx" and choose open with browser. 

The web page will open up.

-------------------------------------------------------------------------
SQL database info for this project:

Instance used : MSSQLlocalDB

Database:[SKL_KOM_INST]

Create Table command:

USE [SKL_KOM_INST]
GO

CREATE TABLE [dbo].[EmployeeDetails]
(
    
    [EmpName] [nchar](10) NULL,
    
    [Mobile] [nchar](10) NULL,
    
    [PresentAddress] [nchar](10) NULL,
    
    [Email] [nchar](10) NULL
    
) 

GO
------------------------------------------------------------------------
//All the best!
