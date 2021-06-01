# Door-Management-
Door management at facility
Steps to run the application
1-	Download the folder “DoorManagement”
2-	Execute the SQL in SQL server 
      CREATE DATABASE [EverBridgeDB]

USE [EverBridgeDB]
GO

CREATE TABLE [dbo].[DoorRecord](
	[Id] [nvarchar](max) NOT NULL,
	[Label] [nvarchar](max) NOT NULL,
	[FacilityId] [int] NOT NULL,
	[IsLocked] [bit] NOT NULL default 0,
	[IsOpen] [bit] not NULL default 0
) 
GO
3-	Change the connection string and start the API project locally (http://localhost:46188)


4-	Strat the WPF client application
