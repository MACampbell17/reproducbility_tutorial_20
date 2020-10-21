# reproducbility_tutorial_20
    1  cd /scratch
    2  git clone https://github.com/MACampbell17/reproducbility_tutorial_20.git
    3  ls
    4  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
    5  bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
    6  ln -s /opt/conda/pkgs/*/bin/* /bin
    7  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
    8  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
    9  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
   10  /opt/conda/bin/pip install bash_kernel
   11  /opt/conda/bin/pip install ipykernel
   12  /opt/conda/bin/python3 -m bash_kernel.install
   13  conda search <PACKAGE NAME>
   14  conda search edgeR
   15  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   16  /opt/conda/bin/conda search -c bioconda snakemake
   17  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
   18  ln -s /opt/conda/bin/* /bin
   19  ln -s /opt/conda/lib/* /usr/lib
   20  snakemake --version
   21  sudo apt-get update
   22  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
   23  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   24  sudo add-apt-repository  "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   25   $(lsb_release -cs) \
   26   stable"
   27  sudo apt-get update
   28  sudo apt-get install -y docker-ce docker-ce-cli containerd.io
   29  docker run hello-world
   30  history
   31  nano
   32  exit
   33  cd /scratch
   34  df -h
   35  ls
   36  cd /scratch
   37  git clone https://github.com/MACampbell17/reproducbility_tutorial_20.git
   38  ls
   39  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
   40  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
   41  ln -s /opt/conda/pkgs/*/bin/* /bin
   42  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
   43  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
   44  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
   45  /opt/conda/bin/conda search -c bioconda snakemake
   46  ln -s /opt/conda/pkgs/*/bin/* /bin
   47  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
   48  /opt/conda/bin/conda search -c bioconda snakemake
   49  cd scratch
   50  sudo apt-get update
   51  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
   52  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   53  sudo add-apt-repository  "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   54   $(lsb_release -cs) \
   55   stable"
   56  sudo apt-get update
   57  sudo apt-get install -y docker-ce docker-ce-cli containerd.io
   58  docker run hello-world
   59  history
   60  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
   61  bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
   62  ln -s /opt/conda/pkgs/*/bin/* /bin
   63  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
   64  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
   65  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
   66  /opt/conda/bin/pip install bash_kernel
   67  /opt/conda/bin/pip install ipykernel
   68  /opt/conda/bin/python3 -m bash_kernel.install
   69  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   70  history
   71  cd /scratch
   72  git clone https://github.com/MACampbell17/reproducbility_tutorial_20.git
   73  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
   74  bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
   75  ln -s /opt/conda/pkgs/*/bin/* /bin
   76  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
   77  sudo apt-get update
   78  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
   79  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   80  sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   81   $(lsb_release -cs) \
   82   stable"
   83  sudo apt-get update
   84  sudo apt-get install -y docker-ce docker-ce-cli containerd.io
   85  docker run hello-world
   86  cd /scratch/reproducibility-tutorial/
   87  history >>README.md
   88  ls
   89  cd /scratch/reproducibility-tutorial_20/
   90  cd /reproducibility-tutorial_20/
   91  cd reproducibility-tutorial_20/
   92  cd /scratch/reproducibility_tutorial_20/
   93  cd reproducibility_tutorial_20/
   94  ls
   95  cd reproducbility_tutorial_20/
   96  history >>README.md
   97  nano README.md
   98  cd
   99  cd
  100  cd scratch
  101  cd /scratch
  102  git clone
  103  git clone https://github.com/MACampbell17/reproducbility_tutorial_20.git
  104  ls
  105  cd reprod*
  106  ls
  107  cd /scratch/
  108  ls
  109  chown -R mac17 /scratch/reproducbility_tutorial_20/
  110  mkdir /scratch/test-workflow
  111  cd /scratch/test-workflow
  112  iget -P /iplant/home/shared/cyverse_training/datasets/PRJNA79729/fastq_files/SRR064156.fastq.gz .
  113  iget -P /iplant/home/shared/cyverse_training/datasets/PRJNA79729/fastq_files/SRR064156.fastq.gz
  114  iget -P /iplant/home/shared/cyverse_training/datasets/PRJNA79729/fastq_files/SRR064156.fastq.gz
  115  cd
  116  /scratch/
  117  cd /scratch/
  118  mkdir -p /scratch/reproducibility-tutorial/experiment/sra_files/metadata
  119  mv SraRunTable.txt /scratch/reproducibility-tutorial/experiment/sra_files/metadata
  120  cd /scratch
  121  git clone https://github.com/MACampbell17/reproducbility_tutorial_20.git
  122  nano
  123  ls
  124  nano repro*
  125  ls repro*
  126  nano READ*
  127  cd /scratch
  128  git clone https://github.com/MACampbell17/reproducbility_tutorial_20.git
  129  cd/scratch
  130  ls
  131  cd /scratch
  132  git clone https://github.com/MACampbell17/reproducbility_tutorial_20.git
  133  sudo apt-get update
  134  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
  135  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
  136  sudo add-apt-repository  "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
  137   $(lsb_release -cs) \
  138   stable"
  139  sudo apt-get update
  140  sudo apt-get install -y docker-ce docker-ce-cli containerd.io
  141  docker run hello-world
  142  cd /scratch/reproducbility_reproducbility_tutorial_20/
  143  cd /scratch/reproducbility_tutorial_20/
  144  history >>README.md
  145  nano README.md
  146  chown -R YOURCYVERSEUSERNAME /scratch/reproducbility_tutorial_20/
  147  chown -R mac17 /scratch/reproducbility_tutorial_20/
  148  scp ~/Downloads/SraRunTable.txt mac17@128.196.142.6:/scratch/
  149  scp ~/Downloads/SraRunTable.txt mac17@128.196.142.6:reproducbility_tutorial_20/
  150  ls
  151  scp ~/Downloads/SraRunTable.txt mac17@128.196.142.6:reproducbility_tutorial_20/
  152  ls
  153  cd /scratch
  154  git clone https://github.com/MACampbell17/reproducibility_tutorial.git
  155  sudo apt-get update
  156  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
  157  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
  158  sudo add-apt-repository  "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
  159   $(lsb_release -cs) \
  160   stable"
  161  sudo apt-get update
  162  sudo apt-get install -y docker-ce docker-ce-cli containerd.io
  163  docker run hello-world
  164  cd /scratch/reproducibility-tutorial/
  165  cd /scratch/reproducibility-tutorial/
  166  cd /scratch/reproducibility_tutorial/
  167  history >>README.md
  168  nano README.md
  169  chown -R mac17 /scratch/reproducibility_tutorial/
  170  cd
  171  ls
  172  cd /scratch
  173  ls
  174  chown -R mac17 /scratch/reproducibility_tutorial/
  175  cd reproducibility_tutorial
  176  ls
  177  cd
  178  cd /scratch
  179  ls
  180  cd /scratch
  181  git clone https://github.com/MACampbell17/reproducibility_tutorial.git
  182  sudo apt-get update
  183  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
  184  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
  185  sudo add-apt-repository  "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
 $(lsb_release -cs) \
 stable"
  186  sudo apt-get update
  187  sudo apt-get install -y docker-ce docker-ce-cli containerd.io
  188  docker run hello-world
  189  cd /scratch/reproducibility_tutorial/
  190  history >>README.md
