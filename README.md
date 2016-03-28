# WordPress-Flush-Notice-Message

This will show a notice only once, in next page reload.

### Usage
$flush = Builder_Flash::get_instance();

$flush->add( __( 'Settings Saved.', 'domain' ) );

$flush->add( array( 'msg' => __( 'Settings Saved.', 'domain' ), 'class' => 'error', 'dismissable' => false ) );
