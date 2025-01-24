# brain_stroke_classification
Data science project to find brain strokes cases on imbalanced datasets. A stroke is a medical condition in which poor blood flow to the brain causes cell death. Prevention includes decreasing risk factors, surgery to open up the arteries to the brain in those with problematic carotid narrowing, and warfarin in people with atrial fibrillation.

## Motivation
Here, I tried to create a machine learning classification algorithm to find futures brain stroke cases. The intuition is to prevent and also to help people that suffer from this diasease, reducing death cases. For that, I have splitted this project in this following parts:

<ol>
    <li>Importing libraries;</li>
    <li>Reading the dataset;</li>
    <li>Analysing the data:
        <ol>
            <li>Dtypes and null values;</li>
            <li>Transform object columns into binary columns;</li>
            <li>Understanding strokes causes;</li>
            <li>Searching for outliers:
                <ol>
                    <li>remove_outliers;</li>
                    <li>box_plot.</li>
                </ol>
            </li>
            <li>Visualising stroke cases;</li>
            <li>Spliting the dataset:
                <ol>
                    <li>splitting;</li>
                </ol>
            </li>
            <li>Solving the imbalanced problem:
                <ol>
                    <li>undersampling;</li>
                    <li>oversamping;</li>
                </ol>
            </li>
        </ol>
    </li>
    <li>Create a classification model:
        <ol>
            <li>Functions:
                <ol>
                    <li>train_model;</li>
                    <li>show_confusion_matrix;</li>
                    <li>show_scores;</li>
                </ol>
            </li>
            <li>Training;</li>
            <li>Evaluating the models;</li>
        </ol>
    </li>
    <li>Choosing the model;</li>
    <li>Saving the model;</li>
    <li>Conclusion.</li>
</ol>
