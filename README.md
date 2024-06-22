# KaggleX-Vehicle-Price-Prediction


**Description**<br>
The skill assessment challenge is a component of the application and will allow the program team to validate your hands-on experience in data science. Please note that the program team will review both your application responses and your skill assessment to determine the status of your application.
<br>
<br>
**Leaderboard**<br>
The leaderboard for this skill assessment challenge is not a reflection of your application standing and does not determine your acceptance.
<br>
<br>
**Evaluation**<br>
Root Mean Squared Error (RMSE)
Submissions are scored on the root mean squared error. RMSE is defined as:
<br>
<br>
RMSE=(1𝑁∑𝑖=1𝑁(𝑦𝑖−𝑦ˆ𝑖)2)12
<br>
<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <mrow class="MJX-TeXAtom-ORD">
    <mtext>RMSE</mtext>
  </mrow>
  <mo>=</mo>
  <msup>
    <mrow>
      <mo>(</mo>
      <mfrac>
        <mn>1</mn>
        <mi>N</mi>
      </mfrac>
      <munderover>
        <mo>&#x2211;<!-- ∑ --></mo>
        <mrow class="MJX-TeXAtom-ORD">
          <mi>i</mi>
          <mo>=</mo>
          <mn>1</mn>
        </mrow>
        <mrow class="MJX-TeXAtom-ORD">
          <mi>N</mi>
        </mrow>
      </munderover>
      <mo stretchy="false">(</mo>
      <msub>
        <mi>y</mi>
        <mi>i</mi>
      </msub>
      <mo>&#x2212;<!-- − --></mo>
      <msub>
        <mrow class="MJX-TeXAtom-ORD">
          <mover>
            <mi>y</mi>
            <mo>&#x005E;<!-- ^ --></mo>
          </mover>
        </mrow>
        <mi>i</mi>
      </msub>
      <msup>
        <mo stretchy="false">)</mo>
        <mn>2</mn>
      </msup>
      <mo>)</mo>
    </mrow>
    <mrow class="MJX-TeXAtom-ORD">
      <mfrac>
        <mn>1</mn>
        <mn>2</mn>
      </mfrac>
    </mrow>
  </msup>
</math>


where 𝑦ˆ𝑖
 is the predicted value and 𝑦𝑖
 is the original value for each instance 𝑖
.
<br>
<br>
**Submission File**<br>
For each id in the test set, you must predict the price of the car. The file should contain a header and have the following format:
<br>
<br>
id,price<br>
54273,39218.443<br>
54274,39218.443<br>
54275,39218.443<br>
etc.<br>

www.kaggle.com/competitions/kagglex-cohort4/overview/evaluation
