import pandas as pd
# Create a dictionary containing the dataset information
data = {
"Dataset Name": [
"Netflix Movies and TV Shows",
"Netflix Movies and TV Shows Till 2025",
"Netflix Movies and TV Shows (Titles and Cast)",
"Netflix Data: Cleaning, Analysis, and Visualization",
"Netflix Users Database"
],
"Source": [
"Kaggle - Netflix Shows",
"Kaggle - Netflix Movies and TV Shows Till 2025",
"Kaggle - Netflix Movies and TV Shows",
"Kaggle - Netflix Data: Cleaning, Analysis and Visualization",
"Kaggle - Netflix Users Database"
],
"Description": [
"A comprehensive dataset listing all movies and TV shows available on Netflix, including details such as cast, directors, ratings, release year, and genres.",
"This dataset contains information on Netflix movies and TV shows sourced from TMDb (The Movie Database), including titles, genres, release years, and more.",
"Contains two files: titles.csv and credits.csv. titles.csv includes movie/show titles, release years, and genres, while credits.csv provides information on the cast and crew.",
"A cleaned version of the original dataset, covering Netflix content added from 2008 to 2021. Ideal for data cleaning, exploratory data analysis (EDA), and visualization tasks.",
"Contains 25,000 fictional Netflix user records, useful for analysis, visualization, and machine learning practice."
]
}
# Convert the dictionary into a pandas DataFrame
netflix_datasets = pd.DataFrame(data)
# Save the DataFrame to an Excel file
excel_file_path = "Netflix_Datasets_Info.xlsx"
netflix_datasets.to_excel(excel_file_path, index=False)
print(f"Excel file saved successfully at '{excel_file_path}'")
EXPLANATION:
Explanation:
1. Import pandas: pandas is a librdry før handling and analyzing data in Python.

   2. Create a dictiondry: data contains Netflix datdset information with columns: Dataset Name, Source, and Description.
3. Convert to DataFrdme: pd. DataFrame (data) transforms the dictiondry into a tabular format, like a spreadsheet.
4. Save ds Excel: to_excel() writes the Data Frame to
Netflix Datasets Info.xlsx.
index=False dvøids saving row numbers.
5. Print confirmation: Prints a success message once the Excel file is saved.
This is ready to copy, run, and understand in one
If you want, 1 can also make a version that shows the table neatly in the vutput beføre saving-that's useful for verification. Do you want me to do that?
OUTPUT:
Dataset NamSoeurce Description
Netflix MovieKsagagnldeT-VNSehtAfloicwxoSsmhopwreshensive dataset listing all movies and TV shows available on Netflix, including details such as cast, directors, ratings, release year, and genres.
Netflix MovieKsagagnldeT-VNSehtTflohiwxisMsdToaivltliae2ss0ea2tn5cdonTVtaSinhsoiwnsfoTrimlla2t0io2n5on Netflix movies and TV shows sourced from TMDb (The Movie Database), including titles, genres, release years, and more.
Netflix MovieKsagagnldeT-VNSehtCfloiowxnMsta(oTivnitiselestswaaonndfidlTeCVsa:Ssthitt)olewss.csv and credits.csv. titles.csv includes movie/show titles, release years, and genres, while credits.csv provides information on the cast and crew.
Netflix Data:KCaglegaleni-nNge, AtAflnicaxllDeysaaintsae,:daCnvldeeraVsnisoinungao,lifAztnahtaeiloyonsrisgiannadl dVaistausaelitz,actoiovnering Netflix content added from 2008 to 2021. Ideal for data cleaning, exploratory data analysis (EDA), and visualization tasks.
Netflix UsersKaDgagtlaeb-aNsetCflioxnUtasienrss2D5a,t0a0b0asfiectional Netflix user records, useful for analysis, visualization, and mac
