Dear INTEGRAL users,

ISDC, University of Geneva, EPFL, and APC Paris have developed the Multi-Messenger Online Data Analysis (MMODA) to obtain high-level science products from several instruments.

    INTEGRAL
        IBIS/ISGRI
        JEM-X
        SPI-ACS
    Antares
    Polar

MMODA can be accessed through a web interface at

https://www.astro.unige.ch/mmoda

or using a convenient python API, see tutorials at

https://oda-api.readthedocs.io/en/latest/

These are the main characteristics of this release

User accounts

    The user of ODA should login to use the service efficiently so that
        They will receive an email upon both job submission and completion
        Upon login, the limit of INTEGRAL science windows is 500 instead of 50 for the anonymous user
        Specific users can access private data upon usage agreement
        Access to HPC resources can be granted abd the limit of 500 science windows raised upon special agreement
        As before, all submitted requests are eventually satisfied, even if they experience issue. In addition, registered users will receive a dedicated follow-up, explaining reasons of failures or suggestions to optimize a difficult request.

New parameters

    The user can specify the number of science windows to be analyzed within a given time interval
    the use can specify to access private data (upon granting of privileges)
    OSA11.2-beta is available for use by restricted user group (this contains the new IBIS/ISGRI energy calibration and spectral response for the full mission)

User experience

    A banner on the web interface reports news and current issues
    A user can received personalized feedback on their job
    python API code has more logging and functionalities, like asynchronous requests
    Images are visualized with js9 (an extension of ds9)
    Help pages are updated and extended

Computation in University of Geneva Back-end facility

    a new Kubenetees cluster makes requests faster
    a powerful HPC cluster is available upon agreement for very large jobs

Known limitations

    In normal use, no more than 50 new requests per hour can be submitted. Note that this will yieild 100 emails. We consider that this is rarely needed, but if necessary, we can provide enhanced access.
    At the moment, OSA11 ISGRI analysis is limited to after revolution 1626. As soon as OSA 11.2-beta is sufficiently stable, it will be made available to everybody.

We invite interested users to *register to the web interface (sign up)* to fully exploit our new developments and to read our A&A paper for a more detailed description of the online data analysis for INTEGRAL instruments. https://www.aanda.org/articles/aa/abs/2021/07/aa37850-20/aa37850-20.html

We can be contacted at the email contact@odahub.io 

Best wishes from the MMODA team.

Volodymyr Savchenko, Gabriele Barni, Mohamed Tahr Meharga, Carlo Ferrigno, Andrii Neronov, Denys Savchenko (with the previous contribution by Andrea Tramacere)
