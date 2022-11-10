jupyter notebook version: read_file_and_plot.ipynb
python script version: read_file_and_plot.py

To run from terminal 
python read_file_and_plot.py 4 'ps' 'fs' './dist-end-to-end.agr' 'example_test'

#command line interface intput:
#python3 read_file_and_plot.py Simulation_time, simulation_time_unit, time_step(eg:ps/ns/fs), simulation_output_file_path, output_filename(eg:test_out1) 

#to test this module: python3 read_file_and_plot.py 4 'ps' 'fs' './dist-end-to-end.agr' 'example_test'



#inputs description
sys.argv[0] = Simulation_time,
sys.argv[1] = simulation_time_unit(ps), 
sys.argv[2] = time_step(eg:ps/ns/fs), 
sys.argv[3] = simulation_output_file_path, 
sys.argv[4] = output_filename(eg:density_out1)

output:
output_filename.csv, output_filename.png and output_filename.xlsx are generated in the ./output dir.