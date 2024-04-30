# tensorCharacterisation
In this file one could find the tensors characterised under the linear action of (S4 \wr S3) \times \mathbb{Z}_6.

The file 3x3char_final.pickle contains the 320 groups that give us all the tensors characterised by their symmetries.
In order to access the groups, one must use Python and its library pickle. Additionally, to use the groups the computer should have the library SageMath downloaded, and using the GAP interface in SageMath these groups can be accessed, analysed and manipulated. With this, one can run:

with open("3x3char_final.pickle", 'rb') as file:
  characteriserGroups = pickle.load(file)

to get the desired groups.
