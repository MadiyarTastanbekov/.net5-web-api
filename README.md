DROP TABLE [dbo].[AuthUser]
GO

/****** Object:  Table [dbo].[User1]    Script Date: 17.02.2024 17:54:58 ******/
SET ANSI_NULLS ON
GO

SET QUOTED_IDENTIFIER ON
GO

CREATE TABLE [dbo].[AuthUser](
	[id] [int]  identity(1,1),
	[Email] [nvarchar](50) ,
	[Password] [nvarchar](max) ,
	[Username] [nvarchar](50) 
) ON [PRIMARY]
GO